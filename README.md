# L01-Dancer
“Why do we dance together? To heal, to remember, to say: we speak a common language, we exist, and we are free.”
https://youtu.be/dpCBMwAweDI?si=1CvRF1ssOD21Zbi7

Today we’ll be building our first character in Unity:

A dancer. A poet. A rebel. Let their motion be the decider.

Objectives:

### Part 1: Adding Animations
Skills Needed: Navigating Unity, Combining Objects
[video link: navigating and making objects]

Add the `Idle X` or `Idle Y` character to your scene. Create and attach an Animator Controller.

Open the Animator and drag the idle animation you selected into the animator.

### Part 2: Animation Switching
Skills Needed: Triggers
[video link: trigger and anim transitions]

Add a dance animation to the animator with a Trigger to switch between idle and dance.

### Part 3: Animation Control from Script
Skills Needed: References in C#, Code Control if (), Code Lookup, Composite Object Model

Create a new Monobehavior Script and attach it to your character.
<br>Either: 
- Add a public variable to the Animator so you can attach it in the editor
- GetComponent the Animator in the Start method and store a class-level reference to it

In the Update method, add a control statement to check Input.GetKeyDown, and activate the Animator's previously attached trigger. 

### BOSS MODE (Optional)
Create a Miaximo Account www.mixamo.com

Download new dance animations to add to the scene. Add more keyboard inputs to switch between animations.

Download a new character model to replace the generic character.

### Reflection
What would the character’s motion be like if they were not allowed to move freely — not allowed to dance? 
