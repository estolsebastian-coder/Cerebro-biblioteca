---
type: libro
title: "sample_animation_guide"
author: ""
categoria: "AYUDAS DE PROGRAMAS"
paginas: 18
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/3D MAX Y VRAY/MODELOS/Nueva carpeta/Scenes/Crowd/Sample_Animation/sample_animation_guide.pdf"
convertido: 2026-10-16
---

# sample_animation_guide

> Texto extraído de `AYUDAS DE PROGRAMAS\3D MAX Y VRAY\MODELOS\Nueva carpeta\Scenes\Crowd\Sample_Animation\sample_animation_guide.pdf` (18 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

A Sample Animation

This document describes the work done on a short animation that comes with the tutorial
files for character studio  4.

All the files related to this project can be found in the sample_animation folder on the
Learning and Training CD. Feel free to explore and look at them, using this document as
a guide.

The purpose of this project is to show how some the character studio features can be
used together to solve different aspects of an animation project.

This is not a tutorial nor a detailed documentation of character studio features, but a
more general description about the workflow, and a resource for tips and suggestions. It
will be helpful for beginners to plan their own work and for non-users to get an
introduction to some of the character studio features.

A general knowledge of character studio 4 is necessary to understand many of the
features introduced. To learn about these features, please check the User Reference and
the Tutorials.

For non-character studio users, this can still be interesting reading about some of the
product features, and can be used to help you evaluate the software.

It would be impossible to create an animation using all the features of character studio
this project focuses primarily on keyframed animation, the Motion Mixer, and crowds.
We don’t use motion-capture files, the Workbench, props, or many of the crowd features.

The Characters
We wanted the characters to be quite different from each other and to use a mix of
features. While character studio is made specifically for bipedal characters, it’s flexible
enough to handle quadrupeds and characters that are not human-like.

<!-- p. 2 -->

Treepy
We wanted Treepy to be a character with a
very disproportionate body. The feet are
practically attached directly to the body, he
has no neck or head, and he has long toes
and fingers, and an extremely limited range
of movements.
Treepy uses Physique to deform the body
mesh.
The model for this character can be found
in models\treepy_physique.max.

Wally the Walier
Wally is a character that can walk on two
or four legs, and fly. Arms and legs need
careful animation to avoid intersecting each
other; it was an interesting challenge to
create all the clips used in this project.
The wings are standard 3ds max bones
attached to the biped structure.
Wally uses the Skin modifier to deform the
body mesh.
The model for this character can be found
in models\walier_skin.max.

Treepy and Wally were modeled rotated 90-and 180-degrees in respect to the standard
biped orientation (facing forward in the Front viewport). Then they were rotated to the
standard position. This was done as a test, and some side effects were encountered during
the project. While nothing was a problem that couldn’t be fixed in a couple of mouse
clicks, we suggest you always model your characters facing forward, so no
transformations need be applied.

<!-- p. 3 -->

The Animation
As for the characters, we tried to use different features for the animation. In character
studio, animation can be created by hand (keyframing each part of a character), by
mixing clips with Motion Mixer, or as part of a crowd using clips in Motion Flow.

Wally was used twice, as a standalone character and as source character for a crowd. The
standalone character was animated using Motion Mixer and various clips, some of them
also used for the crowd animation. The crowd shares some clips with Wally, plus all the
ones necessary for running and turning.

Treepy, instead, was entirely keyframed, since his animation depends on the animation of
the other characters in the scene. Wally and the crowd timing was not 100% predictable
because they were animated by mixing clips and by the crowd system, so Treepy had to
be animated last.

The story is very simple. Treepy’s quiet day is disrupted by the arrival of a horde of
running waliers. Fortunately, Wally announces their arrival and thus prepares Treepy to
deal with the situation.

Preparing the Characters
Treepy uses Physique for the skinning. Since Treepy is a character with a stretchy body,
Physique provided the best solution with its highly deformable envelopes. No manual
weighting of vertices was necessary.

Some of the envelopes used for Treepy.

Wally, on the other hand, uses Skin because his body is more rigid, and because Skin
provides a better way to manually fix the weights of the vertices around the shoulders and
hips. Those areas had to be adjusted manually to obtain the desired weighting.

<!-- p. 4 -->

Red polygons show where manual weight
adjustment was necessary to get the correct
deformation.

Note also that the unusual size of Wally’s head required a properly shaped biped head to
allow for proper animation. A properly sized reference was necessary since, when
preparing clips, it’s preferable to use just the biped with no skin.

The head was created by detaching the real
head from the character body mesh, closing
the hole at the neck, and using an Edit
Mesh modifier on the biped’s head object
to delete the old geometry and attach the
new head.

Planning for the Animation
The first task was to prepare the clips that Wally uses when he enters the scene and
approaches Treepy, and the ones that are used by the rest of the waliers in the crowd.
For Wally, we created a set of clips for walking on two or four legs, turning, looking
around, and taking off.
For the crowd, we needed running cycles, start-and-stop running, various degrees of
turning, and a few loitering clips for when they stopped.

The crowd behavior was another important thing that needed to be planned. We wanted
our waliers to run, stop randomly to sniff the ground, look around or turn, and then start
running again. All this, while running within the camera field and avoiding each other.

<!-- p. 5 -->

Preparation of the Clips
For Wally, we prepared a two-legged walk cycle, a four-legged walk cycle, a 45-degree
turn to the right and the left, a gesture telling Treepy to move over, and a take off when
he leaves the scene. An additional clip was used to add some head motion to the walk and
other neck corrections during a turn.

clips\walier_clip_walk2_all.bip (max file also available)
clips\walier_clip_walk4_all.bip (max file also available)
clips\walier_clip_Lturn45.bip
clips\walier_clip_Rturn45.bip
clips\walier_clip_handsignal.bip
clips\walier_clip_takeoff.bip

For the crowd, we created a running cycle, run-stop and run-start clips, left and right 30and 90-degree turns while running, and left and right sideways-running motions.
The loitering clips have the character sniffing the ground, standing up and looking
around, and we also reused the two 45-degree turns used for Wally.
These clips are enough for the crowd to do all the actions we planned.

clips\walier_clip_run_rotfix.bip
clips\walier_clip_run_runstop.bip
clips\walier_clip_run_runstart.bip
clips\walier_clip_run_L30.bip
clips\walier_clip_run_R30.bip
clips\walier_clip_run_L90.bip
clips\walier_clip_run_R90.bip
clips\walier_clip_sniff.bip
clips\walier_clip_standup.bip

If you look at the clips, you will see that the ones where the character is standing still,
have a 10 leading or trailing frames. For example, the sniff clip has 10 frames at the
beginning and 10 frames at the end where the character is keyframed in its resting
position. The start-run clip has 10 frames at the beginning only, the stop-run clip has 10
frames at the end only.

<!-- p. 6 -->

In 1, 2, 6, and 7, the character is keyframed in its resting position to create a few frames to facilitate
transitions. In 3, the character starts walking. In 4, the character makes a one-and-a-half walk cycle,
and in 5, it stops.

The reason for these 10 frames is to make it easier to create transitions between clips, and
to allow more timing flexibility. You can use these 10 frames to add a moment of rest and
to have a very precise overlap and smooth transition. If you don’t want any moment of
rest, you can simply trim those frames out when editing the transition.

A clip (2) with leading and trailing frames (1 and 3) can be used for a slow transition mixing the
resting frames (4), as well as a fast one mixing the two actions (5).

The clips where the character is running have some overlapping to make the transition
easier and keep the cycle complete. They have an extra half cycle that can be used
entirely or partially for the transition.

In this running clip, half (3) of the complete cycle (1) is duplicated at the end (2) to be used for the
transitions.

<!-- p. 7 -->

The running clips have a separate start run, stop run and run clips, while the walking
cycles (with two and four legs) have a single clip where the character starts walking,
walks for a few steps, and then stops.

The reason for this choice is that the running clips are used in Motion Flow, while the
walking ones in Motion Mixer. Motion Mixer allows an easier clipping of the start and
stop parts of the walking cycle if we want to create a continuous walk, while Motion
Flow works better when those segments are separated.

Depending on your style, you can choose to create multi-actions clips as for the walks
and save and properly name the segments when you save the BIP file, but that requires
some extra efforts to track where each segment starts and ends.

Separating a combination of actions into different clips can be done using segments when saving a
BIP file. This system guarantees excellent overlapping and smooth transitions.

All the clips used in this sample animation have been saved without using segments from
the MAX file. If you want, you can experiment and separate the walk cycles and create a
walking crowd instead of the running one.

Clips Consistency
To make sure the resting position was the same on all clips, we created a template file
with the character in the resting position and the leading and trailing frames already
keyframed, and created each clip starting from that file.

<!-- p. 8 -->

A template file with the character already keyframed in the resting position. Animation can be added
between keys 2 and 3.

When trying to match other positions, we merged temporarily the other biped from the
other clip and aligned their body positions.

To match a position during a cycle overlap (like the running cycle, which is actually oneand-a-half cycles), we made extensive use of the copy and paste feature for posing arms,
head, and tail at different frames.

Copying (at time 1) and pasting (at time 2) biped limbs positions to match the position in the clip
cycle as close as possible.

Reference objects were also used to make each step the same length and to keep the
center of mass moving regularly (see file walier_clip_walk2_all.bip and
walier_clip_walk4_all.bip).

<!-- p. 9 -->

Using reference objects to keep the stride equal at each step and to keyframe the center of mass at
specific positions.

In a few cases, we temporarily cloned the biped and shifted its animation keys in Dope
Sheet to have a reference also for the center of mass and to double-check that everything
matched.

Building the Motion Flow Graph

The Motion Flow Graph for the crowd of waliers. The runstop and runstart clips (1 and 3) are used to
go from the running clips (2) to the loitering clips (4).

When building the Motion Flow Graph, make sure you create as many transitions as you
can. This will help the crowd system when solving the crowd.

The probability settings for each transition are meaningful only for the random scriptcreation feature. The crowd system chooses the clips based on necessity. In our case, the
necessity of reaching the goal was in conflict with our plan to have the waliers stop and
loiter before they start running again.

<!-- p. 10 -->

You can use MAXScript to override the default behavior. We will see later how to
achieve this.

Transitions
Transitions between clips are nothing magical, but there can be a fair amount of trial and
error to get just the right ones. The Optimize Transition option gives you a good starting
point in the majority of cases, but some times it’s not where you want it to be and manual
adjustments are necessary.

As we said earlier, each clip in our project was created with transitions in mind. Leading
and trailing frames and overlapping motion are necessary and, if planned well, make the
transitions work much easier. We had the advantage that we created those clips from
scratch, so in most cases there were no more than a few minutes of work on each
transition.

If your clips are generic motion-capture data or clips from various sources, matching
them up might require more analysis and sometimes fixes, if possible, to the original
clips.

All the Motion Flow transitions were created and tested in the file
walier_crowd_moflow.max. There are quite a few manually created Motion Flow scripts
in this file, testing each transition or combinations of motions.

Once the Motion Flow Graph is finalized, you can save it as an MFE file and use it in the
Shared Motion Flow for the crowd. You can keep the walier_crowd_moflow.max file as
your testing benchmark for adjustment that might become necessary later on, and as the
source for the MFE file.

Considerations on Transitions
The clips for this sample animation have been manually created, so don’t expect any
absolute precision out of them. With a bit of more work we could have made them more
precise, but instead we left them as they were and will use them as examples of situations
you might face when working on your own clips.

First, when the clips are joined using transitions, you will have a bit of overlapping, so
that there is a smooth transition. The overlapping takes a bit of each clip and
progressively changes from one motion to the other.

The importance of having some leading and trailing frames can be seen when this
overlapping occurs. If you mix one action into another directly, there will be part of each
that is lost during the transition. The leading and trailing frames allow you to make a
transition, leaving the action 100% intact. If you want to blend the action directly, you
can always edit the transition to strip out those extra frames. In summary, having the
extra frames is always an advantage.

<!-- p. 11 -->

In a case such as a 90-degree turn, transitioning before the end of the action might result
in an incomplete turn. Depending on what you want to do, this might be a problem or not.
Sometimes, actions that are not always exact result in more natural animations.

As an example, take a look at the clips created for the 90-degree turn while running.

clips\walier_clip_run_R90.bip
clips\walier_clip_run_L90.bip

While the clips themselves do effectively make a 90-degree turn, when you make a script
and create the transitions, you will see that two consecutive turns in opposite directions
will not have the character running in the same direction it started, as you would expect.

After a 90-degree left turn, a straight run, and a 90-degree right turn, the character is not running in
the original direction.

For our sample, this is not a problem. The crowd system will use one or more of a
combination of 90- and 30-degree turns. What the crowd will do is not predictable and
the action is more natural with this kind of imprecision.

There are actually two factors causing this odd behavior:
• The first is the one mentioned earlier: the action in the 90-degree turn clips does not
have a leading and trailing space where the character runs straight. Any transition will
overlap the action itself, altering the completeness of the turn.

The transition (2) between a turning (1) and a straight (3) clip affects the degree of turning.

<!-- p. 12 -->

• The second factor is a bit more subtle. The center of mass of the biped determines the
direction of the biped at any given moment. At the end of a clip, that will be the
reference for the orientation of the next clip.
But the center of mass is also used to rotate the pelvis during the running motion. In a
human walk or jog, this might not be an excessive rotation, but in a run motion, and
especially in a very dynamic running motion as used in our clips, this can create
problems when the transition happens at a stage where the center of mass is
noticeably rotated from the direction of the motion.

Orientation of the center of mass during a dynamic run.

As a result, the next clip might be oriented the wrong way. Always pay attention to
the rotation of the center of mass at the beginning and end of each clip where
transitions occur.

As an example, we are providing three versions of the straight run clip:

• clips\walier_clip_run.bip is the original version. Repeating this clip a few times in a
script would cause the character to turn a bit at each transition, even if it was
animated running in a perfectly straight line.

• clips\walier_clip_run_norot.bip is a test where the center-of-mass rotation has been
completely removed. When you repeat the clip, the character runs perfectly straight,
but the pelvis is not animated anymore.

• clips\walier_clip_run_rotfix.bip has the center-of-mass rotation adjusted. When you
repeat the clip, the character is almost perfectly straight, and the pelvis is animated as
desired.

Adjusting the transition might also help. Keep the trajectory of the center of mass visible
when editing transitions, and check the Top viewport to see if the character’s direction is
affected when you adjust the start frames or the transition length.

When creating your own clips and working on the transitions between them, keep in
mind these two factors to avoid weird behavior:
• Use reference bipeds from other clips to align the center of mass properly.
• Have the character run straight for a few frames at the beginning and at the end of a
turning clip.

<!-- p. 13 -->

Motion Mixer
The Wally animation is created using the Motion Mixer. Motion Mixer allows for greater
flexibility in creating transitions and combinations of motions from different clips and
body parts than Motion Flow.

Motion Mixer is a great tool for mixing motion files and creating new motion out of
them. This is necessary when using standard motion-capture files, or when your library of
motions is not as complete as you would like.

For this sample, we created our clips from scratch knowing in advance what Wally would
do. Because of this, we underused the Motion Mixer capabilities, and basically combine a
sequence of clips within a track, taking advantage of the excellent transition handling.
Only some secondary motion to the head and tail is added using a Layer track.

The Motion Mixer for Wally. The lower Transition track (1) is used to combine all the clips. The
upper Layer track (2) is used together with weight curves to add and correct the head motion.

The basic rules for creating clips to be used in Motion Mixer are not that different from
what you would do for Motion Flow. But Motion Mixer’s ability to combine motion from
different clips and body parts gives you the flexibility to create clips for the lower body
and upper body separately.

Note that the four-legged walk at the beginning is the result of two copies of the fourlegged walk clip. Since our original clip for the walk includes the start and stop actions,
we had to trim them out to make it look continuous.

The rest of the transitions were adjusted manually; most of the time was spent
minimizing the time between actions, trimming leading and trailing frames. It was all
done by trial and error, trying to get smooth motion and the timing as natural as possible.

It’s inevitable that transitions will produce output that needs some adjustment. Some
sliding of the feet or awkward movements can be expected.

If your work requires absolute precision, you might want to create a mixdown, copy it to
the biped, and then manually fix all the details. This is not a reversible process: you can’t
go back to the mixer later on and adjust the motion again. You will lose your editing
when you do another mixdown.

Don’t look at the feet sliding while in Mixer mode. That is only a temporary
approximation of the final motion. Check them only after a mixdown. Most of the sliding
will disappear.

<!-- p. 14 -->

In our sample, we did a final cleanup and removed and adjusted some feet-planted keys.
Most of the time, it’s just a matter of enabling the Join To Previous IK Key and delete
unnecessary keys created by the overlapping of the clips.

Also, before the mixdown, we turned off the Enforce IK Constraints option in the Mixer
Preferences dialog. This option is on by default and is generally useful, but in our case,
right after Wally stops, there are a lot of IK keys close together when he turns twice to
the right. Most of those keys were removed when this setting was on.

Attached Objects
3ds max objects attached to the biped are supported in the BIP file format (to exchange
animation between characters), but are not supported in Motion Mixer and Motion Flow.

Wally’s wings are 3ds max bones attached to one of the biped spine segments.

As you can see in our example, when in Motion Mixer mode, the motion coming from
last clip in the Motion Mixer, where Wally takes off, has no animation on the wings.

Since the original clip does have that animation in place, we just need to merge it to
Wally’s wings after the mixdown. This is easily achievable using the standard 3ds max
Merge Animation tool, and adjusting the timing, moving the animation keys for the
wings to the right place in the Dope Sheet editor.

The Crowd
The crowd was developed separately and then combined with Treepy and Wally into the
final file. See the crowd only file walier_crowd_setup.max.

As we mentioned earlier, the crowd has its own logic when choosing clips. The choice
depends on all the behaviors we combined.

In our case, our crowd is running toward a target (see the Seek behavior settings) and at
the same time is constrained between a region by two virtual walls (see the Wall Repel
behavior), with Wander and Avoid behaviors to make the motion more realistic.

But the main goal is to reach the target of the Seek behavior. With this in mind, the crowd
is only interested in running toward that object until it reaches it.
But to make the thing more interesting, we wanted the waliers to stop once in a while,
and do some loitering actions before start running again.

<!-- p. 15 -->

To achieve that effect, we used MAXScript to override the default choice of clips and
force the waliers to stop when they reach the proximity of some objects we called
stopperboxXX.

The crowd of waliers (1) is ready to start. Two walls (2) in the Wall Repel behavior will confine them.
Stopper boxes (3) are visible in the scene and the circles around them are used to have an idea of
their range of action as specified in the script. The waliers will try to reach the final target (4)
specified in the Seek behavior.

During the crowd solving process, a MAXScript function is called for each biped on each
frame. Our override logic works in combination with the Motion Flow Graph.
Since there are some transition that are not possible (you can’t go from a running clip to a
loitering one unless you stop first), we can prepare each biped’s list of preferred clips
during the first time where the function is called (at frame 1), and add the loitering clips.

The loitering clips will remain in the preferred list but will not be chosen until the
characters stop.

We can then start checking at each frame the biped’s proximity to a stopper box and add
the runstop clip as necessary, and clear it when out of the stopper box’s influence. This
makes some of the bipeds stop after going through those areas of influence.

A few areas of influence are bigger to make it more likeably to happen in focus points.

<!-- p. 16 -->

Below is the script used. Notice also that the clip names are case sensitive.

bips = #()

fn PerFrameFn crwd time =
(
if (time == 1f) then
(
format "building biped list\n"
bips = for obj in objects
where (classof obj == Biped_Object and
obj.controller.rootNode == obj) collect obj

format "adding clips\n"
for bip in bips do
(
biped.addprefclip bip.controller "sniff" 0
biped.addprefclip bip.controller "standup" 0
biped.addprefclip bip.controller "Rturn45" -20
biped.addprefclip bip.controller "Lturn45" -20
biped.addprefclip bip.controller "runstart" 0
)
)

for bip in bips do
(
if ((distance $stopperbox01 bip) \< 200 or
(distance $stopperbox02 bip) \< 150 or
(distance $stopperbox03 bip) \< 200 or
(distance $stopperbox04 bip) \< 150 or
(distance $stopperbox05 bip) \< 150 or
(distance $stopperbox06 bip) \< 150 or
(distance $stopperbox07 bip) \< 200 or
(distance $stopperbox08 bip) \< 150
) then
biped.addprefclip bip.controller "runstop" 10
else
biped.deleteprefclip bip.controller "runstop"
)
)

While the file used to create the Motion Flow Graph, walier_crowd_moflow.max,
includes the transition between the stop-run and start-run clips, that transition has been
removed (before saving the MFE file for the shared motion flow) to force the characters
to perform at least one loitering clip after stopping.

During the development of the crowd, tests were done without the use of backtracking.
This made the solving faster, but didn’t guarantee that there were no collisions between
bipeds. It was still useful to test the other behaviors and the MAXScript override logic.

Even with the Avoid behavior in place, when using a crowd of bipeds, the clips limit the
possible movements necessary for them to avoid one other. Remember that in crowd,
most behaviors only apply forces to the bipeds, and those forces determine what the next
clip will be.

Backtracking becomes necessary when using crowds of bipeds. It will allow the crowd
system to recognize collisions effectively and go back and try different clips to avoid it.

<!-- p. 17 -->

This process requires each biped to be solved independently and increases the solution
time noticeably, but if you’ve prepared your crowd properly, all your tests can be done
without backtracking, and only a few tests at the very end will require that it be enabled.

When using a biped crowd, both Solve Start and Simulation Start must be set to zero. Use
the Frame Start for each delegate to delay them. This can be done automatically for all
delegates in the crowd Priority rollout.

In our sample, the delegates that drive each biped have been prioritized and they start
moving progressively from the front to the back. This guarantees a smooth start of the
crowd, with no collisions in the first few frames, where backtracking might easily fail to
find any solution.

The starting frame for each delegate was also set automatically based on the priority,
starting at frame 650 with increments of 2 to 5 frames for each delegate.

Also, in the Motion Flow Graph, we selected most of the running clips as random starting
clips, in order to give as much variety and flexibility as possible to the starting crowd.

Highlighted are the clips that can be randomly used as a start by each individual crowd biped.

Crowd Heaviness
When lots of characters are in a scene, expect the response to be a bit slow. There are a
few things you can do to avoid the situation becoming unmanageable.

First, do all your tests on a smaller crowd. Most of the development of this crowd was
done with just five characters. The number was then increased to 12, and finally to 24 for
the final few tests.

Another thing you might want to consider is to disable all the characters’ body meshes.
Having them during the development stage will only slow things down and make
scrubbing the time slider an impossible task.

<!-- p. 18 -->

We created a selection set for all the meshes so we can hide and show them in a snap.
Using the Selection Sets Editor, you can select each of them quickly and also disable the
Skin and MeshSmooth modifiers to make things even faster.

All the waliers were cloned by merging the same model multiple times, then the resulting
files were renamed. In the current implementation, objects using the Skin modifier cannot
be cloned. If you are not using Skin, a standard clone of the biped is a better solution; you
can rename the whole biped during the cloning.

The delegates animation was not saved, since it was not important for our bipeds crowd
and made the MAX file smaller. To avoid creating keys for the delegates, in the crowd
Solve rollout, set the Save Every Nth Key fields for Positions and Rotations to 0.

Merging Treepy and Wally with the Crowd
It’s not possible to merge a crowd into an existing scene, since the shared motion flow
can’t be imported and you’d thus lose the crowd animation. Make sure you plan
accordingly when working on your animations.

We merged Treepy and Wally from a temporary file where we created their animation.
We also removed all the objects used for the creation of the crowd. Only the bipeds, the
eyes, the wing bones and the skin meshes are useful for the final rendering.

Once we verified that everything was working fine, we completed Treepy’s animation to
react properly to the crowd.

After this, it was just a matter of preparing lights, unhiding the skin meshes, enabling
their Skin and MeshSmooth modifiers, and setting up all the rendering preferences.

Note that the MeshSmooth for the crowd walier has only one iteration. It still provides a
good result, since there are no close-ups, and saves quite a bit of rendering time.
