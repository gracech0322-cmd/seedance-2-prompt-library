# Awesome Seedance 2.0 Prompts Libary (Updated: March 4, 2026)
This is a collection of the best prompts and videos for Seedance 2.0. Learn to make cinematic AI videos with ease here.

## 📖 Table of Contents
* [📄 About this Project](#-about-this-project)
* [🤔 What is Seedance 2.0?](#-what-is-seedance-20)
* [🔥 Featured Prompts](#-featured-prompts)
* [🚀 How to Write Seedance 2.0 Prompts?](#-how-to-write-seedance-20-prompts)

## 📄 About This Project
This is a simple library of "AI video recipes." We share prompts that actually work.
- Copy and Paste: Use our prompts to get great results instantly.
- Save Time: No more guessing. Use proven workflows.
- Free Forever: Open to everyone.

⚠️ Copyright Notice:
All prompts are collected from the community (such as Reddit, X, WeChat, and other platforms) and are shared for educational purposes only. If you are a copyright owner and would like any content removed, please submit a removal request by opening an Issue with relevant details and proof of ownership.

## 🤔 What is Seedance 2.0?
[Seedance 2.0](https://seed.bytedance.com/en/seedance2_0) is a powerful tool for making AI movies. It is better than standard tools because:
- Real Control: Use your own photos and videos as guides.
- No Glitches: Characters stay the same from start to finish.
- Great Sound: Faces move perfectly with the audio.
- High Quality: Every video looks like a real movie.
![seedance2 0 homepage](https://github.com/user-attachments/assets/042b44fe-2493-44aa-a88b-c9f718b18ae1)

## 🔥 Featured Prompts
### No.1 Golden eagle flying through a city and landing
🎬 **Video**


https://github.com/user-attachments/assets/7f752298-b0c8-4057-a428-7e9488d921c7


📝 **Prompt**

```text
Hyper-realistic cinematic footage: A golden eagle takes off from a rocky cliff at dawn, wings spread, feathers clearly visible with aerodynamic drag. It glides forward, banking left to avoid a hanging construction crane cable, then climbs sharply over a rooftop antenna array. Wings flex slightly under air resistance, primary feathers bending independently, interacting realistically with the airflow. Breath steam is faintly visible in the cold morning air during a close flyby. The camera tracks parallel at a medium distance using stabilized aerial equipment, with slight natural shake from wind turbulence. The background reveals a dense city skyline enveloped in morning mist, low-angle eastern sunlight casting long shadows across glass facades. As the eagle's downdraft interacts with the environment, the wind blows loose dust and confetti on the roof. The eagle approaches the roof of a modern concrete high-rise. Through controlled wing flaps, momentum gradually decreases, talons extend forward, muscles visibly tense, and micro-adjustments are made for balance. It lands firmly on a large metal rooftop sign that reads "Ambition". Talons grip the metal surface, causing slight vibration and audible metallic resonance. Center of gravity shifts forward then stabilizes. Feathers naturally fall into place. The eagle scans the horizon with subtle head twitches and blinks. Maintain stable temporal consistency. Avoid unnatural frame interpolation. No exaggerated slow motion. Realistic physics, accurate center of gravity shifts, true avian anatomy, environmental reaction to forces.
```

📌 Details  
Author: OwnDay1819  
Source:   
Published: March 1, 2026

## 🚀 How to Write Seedance 2.0 Prompts?

To create better videos with Seedance 2.0, structure your prompt around these five key dimensions:

| Dimension | What to Think About | What It Means |
|------------|--------------------|---------------|
| I. Input | What reference materials are you using? What is each one for? | List your image, video, or style references and explain their purpose (character look, environment, lighting, motion style, etc.). |
| II. Content | What happens in the scene? (visual + audio) | Describe the characters, environment, actions, emotions, dialogue, narration, and sound effects. Be clear about what is happening. |
| III. Cinematography | How is it filmed? How does the camera move? | Specify camera movement (pan, tilt, tracking shot), shot type (close-up, wide shot), angle, and composition rules. |
| IV. Structure | How is time organized? | Define the timeline. What happens in the first 0–3 seconds? How does the scene transition? What is the pacing? |
| V. Edit | What should change or stay the same? | Clarify the editing goal. Should style remain consistent? Are you modifying motion, lighting, or mood? What is the final output style? |

### Input

This is the entry layer for Seedance 2.0. It shows which files you can use and what they do. It answers one simple question: What should the AI model follow?

You can use the @ symbol to tag three types of assets:

| Input | Use Case |
|------------|--------------------|
| @image | First/last frames, character looks, textures, and scenes. |
| @video | Camera movement, actions, effects, and style. | 
| @audio | Music, voice style, mood, and rhythm. |

When using these assets in your prompts, use the following simple sentence structure:

**Standard Format:**
```text
@[Asset A] as [Use Case], @[Asset B] for [Use Case], @[Asset C] for [Use Case]
```

**Example:**
```text
@Image1 as first frame, @Video1 for camera movement, @Video2 for character motion, @Audio1 for background music
```

### Content
This is the Narrative Core. It answers one simple question: What is happening in the scene?

This layer only describes the story. It does not describe camera angles or timelines. You can think of it like this: What is the actor doing on set? (Ignore the camera for now).

| Element | Meaning |
|------------|--------------------|
| Style| Chinese animation / Commercial / Film / Documentary... |
| Character | Who? Their identity / Appearance / Current state |
| Environment |Where? Lighting / Time of day / Weather |
| Action | What is happening? How are they doing it? |
| Mood/Vibe| Calm / Tense / Warm / Oppressive... |
| Lines/Narration | What is being said? |
| Sound Effects | Footsteps / Crowd noise / Ambient sounds... |

When using these assets in your prompts, use the following simple sentence structure:

**Standard Format:**
```text
[Style]. @[Asset] [Character] in [Environment] is [Action]. [Character] with [Emotion] says "[Lines]". Background is [Sound Effects].
```

**Example:**
```text
Commercial Style. The girl from @Image1 is by the window in the early morning. She slowly lifts a cup of coffee and takes a sip. She smiles and whispers, "So good." Relaxed and happy music plays in the room.
```

### Cinemetography

This layer answers the question: How does the camera move? It does not care about what is being filmed (the previous layer handles that). 

In a real movie set, this is where you focus only on the camera's path and ignore the actor's lines or expressions.

To get the best results, use these five elements:
| Element | Examples |
|------------|--------------------|
| Shot Size | Long shot / Medium shot / Close-up / Extreme close-up... |
| Camera Angle | Eye level / High angle / Low angle / POV (First-person)... |
| Movement | Static / Zoom in / Zoom out / Pan / Tilt / Crane shot... |
| Camera Rules | One-take / No cuts / Match cut... |
| Movement Speed | Slow to fast / Steady / Subtle handheld shake... |

Important: When describing camera language, use rules, not adjectives.

Don't write: "High-quality" or "Cinematic feel."

Do write: "One-take," "Steady follow shot," or "Transition from medium to close-up."

**Standard Format:**
```text
From [Camera Angle], [Movement] to [Shot Size], using [Camera Rules].
```

**Example:**
```text
Based on the outdoor scene in @Image1, use a first-person POV to fast zoom into a medium shot of the cabin interior. A deer (@Image2) and a sheep (@Image3) are chatting by the fire. Zoom in further to a close-up of the teacup. No cuts, one-take throughout.
```

### Structure

This section acts as the pre-production layer for Storyboarding and Editing. It focuses on timing and sequence to ensure the final output has a professional rhythm.

Timeline & Sequence Layer
This layer answers the question: How does the time flow and connect? Its purpose is to control the rhythm precisely by the second, rather than relying on "feeling."

Key Components
To build this layer, you need to focus on:

- Timeline Splits: Breaking the prompt into specific segments (e.g., 0–3s, 3–6s, 6–9s).

- Segment Content: What happens in the frame or camera for each part.

- Transitions: How one segment moves to the next.

- Coherence Logic: Ensuring the story flows naturally.

How to Build Your Prompt
First, build your framework by splitting the time. Then, fill each segment with the Assets (I), Content (II), and Camera (III) details we discussed earlier.

**Standard Structure:**
```text
0–X seconds:

[I @Assets / II Content / III Camera]

X–Y seconds:

[I @Assets / II Content / III Camera]
(Note: Do you need a change in action or emotion here? How should the camera transition?)

Y–Z seconds:

[I @Assets / II Content / III Camera]
(Note: Is there a plot twist or a key piece of information?)

Ending (Optional):

[Closing Method: Freeze frame / Camera stop / Lingering emotion]
```

**Example:**
```text
0–3s: An alarm clock rings; the room appears with a blurry, "dreamy" look.

3–10s: A fast pan reveals a close-up of a man’s face.

10–12s: A girl pouts and hides under the covers.

12–15s: Cut to a full-body shot of the man; he sighs and says, "I give up with you!"
```

### Edit

This section covers the video editing capabilities of Seedance 2.0. It is designed for when you have an existing video and want to modify it rather than starting from scratch.

This layer answers the questions: What do I want to change, and how do I change it?

4 Types of Video Editing:

| Editing Type | Usage |
|------------|--------------------|
| Extend | Connects to the final frame and adds [X] more seconds.
| Partial Edit Modifies | specific elements, such as hair color or clothing. |
| Replace | Keeps the overall scene but replaces the protagonist or product. |
| Re-Plot | Keeps the characters and environment but rewrites the entire story. |

How to Write Editing Prompts?

Define the Type: 

- Start by stating if you are extending, replacing, or re-plotting.

- Specify the Target: Clearly mark which part needs changing. Is it from second X to Y? A specific action? A certain element?

- Set Constants: Emphasize what must stay the same, such as the art style, camera movement, scene, or character consistency.

**Standard Format:**
```text
[Action] @Video1 (Extend by [X]s / Re-plot / Replace [A] with [B]), [New Details: I @Assets / II Content / III Camera], while keeping the original [Style/Camera/Character].
```

**Example:**
```text
Re-plot @Video1. The character picks up the phone instead of walking away. Use @Image1 for the new phone design. Keep the original cinematic lighting and medium shot camera angle.
```
