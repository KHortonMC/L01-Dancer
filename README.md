# L01-Dancer
A hello Unity lab demonstrating a dancer character.

“Why do we dance together? To heal, to remember, to say: we speak a common language, we exist, and we are free.”
https://youtu.be/dpCBMwAweDI?si=1CvRF1ssOD21Zbi7

Today we’ll be building our first character in Unity:

A dancer. A poet. A rebel. Let their motion be the decider.

Objectives:

- Part 1: Adding Animations
- Add the Idle X or Idle Y character to your scene
- Create and attach an Animation Controller
- Open the Animation Controller and add the Idle animation
- Set the Idle to default
- Next, return to the animator and add a dance animation
- Add a transition from the Idle to the dance animation
- Run the game -- at the end of the Idle, the dance will begin!

- Part 2: Animation Switching
- In order to change animations, we'll need a Trigger
- (Triggers are events that happen once)
- Add a trigger named 'dance' 
- Set the animation to transition when the trigger runs
- Test the transition by selecting the circle next to the trigger

- Part 3: Animation Control From Script
- Create a new Monobehavior Script 
- Attach your script to your character
- Open the script in Visual Studio Code
- To connect our custom script to the animator:
- Animator myAnimator = GetComponent<Animator>();
- We can now set myAnimator.SetTrigger("dance");
- In the Update method, check:
- Input.GetKeyDown(KeyCode.Space) 

- BOSS MODE (Optional): Create a Miaximo Account www.mixamo.com
- Download a new dance animation to add to the scene
- Use the keyboard to change between your animations!
- Find a new character to replace the dancer

- REFLECTION: What would the character’s motion be like 
  if they were not allowed to move freely — not allowed 
  to dance? 
