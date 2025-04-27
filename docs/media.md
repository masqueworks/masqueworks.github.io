---
title: Media Window
layout: default
nav_order: 5
parent: Documentation
---

# Media Window

![](../Images/Masque_Media.png){ width=30% }

## Media Properties and Instancing

The Media Window allows duplicating media so multiple versions can be referenced with different properties without modifying the original source data. Selecting a media entry and clicking the Duplicate button creates an identical Media entry in the Media Window.

Modifiable properties include:

- **Start and Duration** - Adjust the start time and duration to create sub-clips or loop segments.
- **Looping** - Enables infinite looping of the media instance.
- **Visual - Blend Type** - Defines how a visual image composites with other visuals:
  - **Alpha** - Blends based on the alpha channel (default).
  - **Add** - Adds the image values on top of the existing channel (used for rain/snow effects with a black background).
  - **Multiply** - Multiplies the image value with the underlying value.
  - **Vignette** - Blends using the inverted alpha value (used for vignette effects).
- **Audio - Gain** - Adjusts the gain of the media.
- **Audio - Pan** - Modifies panning between left and right channels.
- **Audio - Pitch** - Alters pitch, useful for recomposing music (extreme adjustments may degrade sound quality).

## Channel Effects

Channel Effects dynamically drive channels to create effects like flickering flames or magical energy ramp-ups.

To create an effect:
1. Click the Add Effect button in the Media Toolbar.
2. In the Property Editor, add multiple effects targeting specific channels (e.g., intensity, fade, pan).

Effect types:

- **Static** - Specifies a fixed value for the channel.
- **Wave** - Generates a sine wave effect.
- **Pulse** - Creates a pulsing effect.
- **Cycle** - Cycles between multiple values.

Common effect properties:

- **Frequency** - Determines how often (in seconds) the effect repeats.
- **Offset** - Defines the starting point within the effect when first triggered.
- **Randomize** - Introduces randomness to the effect.
- **UniqueInstance** - Assigns a unique starting offset and seed values per gizmo (useful for independent light flickers).

To assign an effect, drag it onto the Channel Window when a Gizmo is selected, onto the Gizmo itself, or as a Play Effect action in a cue.

## Shader Effects

Shader Effects provide advanced visual effects that enhance video and images displayed on a Visual Gizmo.

For examples, visit: [ShaderToy](http://www.shadertoy.com).

Shader Effects are a type of media file requiring hand-editing. Existing shader effects in Masque can be explored to understand how to:
- Define **controllable parameters**
- Write **shader code** that interacts with those parameters

---

