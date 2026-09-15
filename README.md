# Ex.No.9 – Exploration of Prompting Techniques for Video Generation

# Date: 16.09.2026

# Reg. No.: 212224040141

## Aim:

To demonstrate the ability of text-to-video generation tools to reproduce an existing video by crafting precise prompts. The goal is to identify key elements within the video and use these details to generate a video as close as possible to the original.

The experiment also aims to explore how different prompt structures, such as simple prompts, detailed prompts, style-based prompts, motion-based prompts, and iterative refinement, affect the quality, coherence, realism, and consistency of generated videos.

---

# Tools / LLMs Required

* ChatGPT
* Google Gemini
* Sora or other available text-to-video generation tools
* Stable Video Diffusion or other video generation models
* Midjourney or other supporting generative AI tools

---

# Selected Video for the Experiment

A **serene mountain landscape during sunset** is selected as the reference video.

### Description of the Original Video

The reference video contains:

* A wide mountain valley
* Snow-covered mountains in the background
* A calm river flowing through the valley
* Green trees and vegetation along the river
* A golden-orange sunset
* Purple, pink, orange, and blue clouds
* Sunlight reflecting on the river
* Slow and smooth camera movement
* Natural atmospheric lighting
* Photorealistic cinematic appearance

---

# Procedure

## Step 1 – Analyze the Original Video

The reference video is carefully examined to identify its major visual and motion characteristics.

### Video Analysis

| Feature     | Observation                                           |
| ----------- | ----------------------------------------------------- |
| Subject     | Mountain valley and river                             |
| Background  | Layered snow-covered mountains                        |
| Foreground  | River, rocks, grass, and trees                        |
| Sky         | Orange, pink, purple, and blue clouds                 |
| Lighting    | Warm sunset lighting                                  |
| Time        | Golden hour / sunset                                  |
| Water       | Calm flowing river with reflections                   |
| Camera      | Slow cinematic movement                               |
| Style       | Photorealistic                                        |
| Mood        | Peaceful and scenic                                   |
| Composition | Wide landscape shot                                   |
| Motion      | Flowing river, moving clouds, gradual camera movement |

### Sample Output

> The video shows a peaceful mountain valley at sunset. A wide river flows through the foreground and reflects the warm orange and golden sunlight. Tall evergreen trees and green vegetation surround the river. Snow-covered mountains form multiple layers in the background. The sky contains dramatic clouds with purple, pink, orange, and blue tones. The camera moves slowly across the landscape, creating a smooth cinematic effect. The overall mood is calm, natural, and majestic.

---

# Step 2 – Generate the Initial / Original Video

The first video is generated using a simple prompt. This represents the **initial video output** before detailed prompt refinement.

### Initial Video Generation Prompt

> Generate a short photorealistic video of a serene mountain landscape during sunset. Show snow-covered mountains in the background, a calm river flowing through the valley, green trees and vegetation along the riverbanks, and a colorful sunset sky. The scene should look peaceful and natural, with warm golden sunlight reflecting on the river. Use a wide landscape composition and gentle natural movement.

### Sample Initial Video Output

**Scene 1 – Opening**

> A wide view of a mountain landscape appears during sunset. Snow-covered mountains are visible in the background.

**Scene 2 – River**

> A calm river flows through the valley, with trees and vegetation along both sides.

**Scene 3 – Sunset**

> Warm orange and golden sunlight illuminates the mountains and reflects on the river.

**Scene 4 – Movement**

> The camera slowly moves through the landscape while the river and surrounding vegetation show gentle natural movement.

### Initial Output Evaluation

The initial prompt successfully produces the basic concept of the reference video. However, several details are not sufficiently controlled.

### Limitations

* Mountain shapes may differ from the reference.
* Exact camera movement is not specified.
* Cloud movement is not clearly defined.
* Water movement may be limited.
* Tree movement may be inconsistent.
* Exact sunset position is not specified.
* Temporal consistency is not explicitly controlled.
* The generated composition may vary from the reference.

Therefore, the initial prompt is refined further.

---

# Step 3 – Create the Basic Prompt

A simple prompt is created to establish the main visual concept.

### Basic Prompt

> A serene landscape with mountains and a river during sunset.

### Sample Generated Output

> A mountain landscape is shown during sunset with a river flowing through the valley. The scene contains warm sunlight and a peaceful natural environment.

### Evaluation

The basic prompt identifies the main subject but does not provide enough information about:

* Objects
* Colors
* Lighting
* Camera movement
* Environmental motion
* Style
* Composition

Therefore, additional details are added.

---

# Step 4 – Refine the Prompt with More Detail

### Detailed Prompt

> A serene mountain valley during sunset, with snow-covered mountains in the background and a calm river flowing through the valley. Green trees and vegetation line both sides of the river. The sky contains purple, pink, orange, and blue clouds. Warm golden sunlight illuminates the mountains and reflects across the surface of the river. The scene is peaceful and cinematic.

### Sample Generated Output

> The generated video presents a mountain valley during sunset. Snow-covered mountains appear in the distance while a river flows through the center of the scene. Trees and vegetation are visible along the riverbanks. The sky contains warm sunset colors, and the river reflects the golden light.

### Evaluation

The detailed prompt produces a closer representation of the reference because it provides information about the environment, colors, lighting, and composition.

---

# Step 5 – Add Motion Information

Since the experiment focuses on **video generation**, motion-related instructions are added to the prompt.

### Motion Prompt

> A photorealistic cinematic mountain valley during sunset. A calm river slowly flows through the foreground while its surface reflects the golden-orange sunlight. Snow-covered mountains remain stable in the background. Evergreen trees and grass move gently in a light breeze. Clouds slowly drift across the purple, pink, orange, and blue sky. The camera performs a slow smooth forward movement along the river, gradually revealing the mountain valley. Use natural motion, realistic water movement, stable mountains, and smooth camera movement.

### Sample Generated Output

**Beginning:**

> The camera starts with a wide view of the river and surrounding vegetation.

**Middle:**

> The camera slowly moves forward along the river. The mountains remain stable while the clouds move gradually across the sky.

**End:**

> The camera continues toward the distant mountains while the sunset reflection becomes more prominent on the river.

### Evaluation

Adding motion instructions improves temporal consistency and makes the generated result more suitable for video generation.

---

# Step 6 – Identify Style and Artistic Influences

### Style Prompt

> Generate a photorealistic cinematic nature video showing a serene mountain valley at golden hour. Use realistic landscape photography, natural atmospheric depth, cinematic composition, realistic water reflections, detailed vegetation, soft volumetric sunlight, and natural cloud movement. Maintain a peaceful documentary-style appearance rather than an artificial or animated look.

### Sample Generated Output

> The resulting video has a realistic photographic appearance. The mountains have natural textures, the river contains realistic reflections, and the sunset lighting creates atmospheric depth. The overall scene resembles professional cinematic landscape photography.

### Evaluation

The style prompt improves:

* Photorealism
* Lighting
* Atmospheric depth
* Natural textures
* Cinematic appearance
* Visual consistency

---

# Step 7 – Adjust and Fine-Tune the Prompt

After comparing the generated video with the reference, additional instructions are added for camera movement, environmental motion, object stability, and unwanted elements.

### Final Refined Video Generation Prompt

> Create a high-resolution, photorealistic cinematic video closely matching the reference mountain landscape.
>
> Show a wide alpine valley during golden-hour sunset. A calm river flows continuously through the foreground toward the distant valley, with realistic subtle ripples and reflections of the golden sunlight. Rocky riverbanks, green grass, shrubs, and tall evergreen trees surround both sides of the river.
>
> In the background, maintain multiple layers of majestic snow-covered mountains with realistic atmospheric haze and depth. The sky contains dramatic but natural clouds in orange, golden, pink, purple, and blue tones. Keep the sun low near the right side of the mountain ridge, producing warm rays and a long golden reflection across the river.
>
> The camera should move very slowly and smoothly forward along the river, maintaining the same wide panoramic composition throughout the shot. The river should continuously flow, clouds should drift slowly, and trees and grass should gently move in a light breeze.
>
> Keep the mountains, rocks, riverbanks, and major landscape structures stable without morphing or changing shape.
>
> Use realistic landscape photography, natural cinematic lighting, atmospheric perspective, detailed vegetation, realistic water physics, smooth camera movement, and strong temporal consistency.
>
> Do not add people, buildings, vehicles, animals, text, logos, artificial objects, cartoon effects, fantasy elements, sudden camera movements, rapid zooms, camera shake, scene cuts, or object deformation.
>
> The final result should look like a real professional camera recording the same mountain landscape, with natural motion added to the environment.

---

# Step 8 – Generate the Final Video

The final refined prompt is entered into the selected text-to-video generation model.

### Sample Final Video Output

**Scene 1 – Opening**

> The video begins with a wide panoramic view of the mountain valley. The river occupies the foreground while layered snow-covered mountains appear in the background.

**Scene 2 – Camera Movement**

> The camera slowly and smoothly moves forward along the river while maintaining the wide landscape composition.

**Scene 3 – River Movement**

> The river continuously flows through the valley. Small ripples move across the surface and reflect the warm sunset colors.

**Scene 4 – Vegetation**

> Evergreen trees, grass, and shrubs gently move in a light breeze while remaining naturally positioned along the riverbanks.

**Scene 5 – Clouds**

> Purple, pink, orange, and golden clouds gradually drift across the sky.

**Scene 6 – Sunset**

> The low sun remains near the right side of the mountain ridge, creating warm rays and a long golden reflection across the river.

**Scene 7 – Ending**

> The camera continues its slow forward movement toward the distant mountains, maintaining a peaceful cinematic appearance.

---

# Step 9 – Compare the Original and Final Generated Videos

The original and final generated videos are compared based on visual characteristics and motion.

| Feature              | Original Video                 | Final Generated Video          | Observation     |
| -------------------- | ------------------------------ | ------------------------------ | --------------- |
| Mountains            | Snow-covered layered mountains | Snow-covered layered mountains | Closely matched |
| River                | Calm flowing river             | Calm flowing river             | Closely matched |
| Sunset               | Orange/golden sunset           | Orange/golden sunset           | Closely matched |
| Sky                  | Purple, pink, orange clouds    | Similar colored clouds         | Good match      |
| Trees                | Evergreen vegetation           | Evergreen vegetation           | Good match      |
| Lighting             | Warm golden light              | Warm cinematic light           | Good match      |
| Water Reflection     | Strong sunset reflection       | Visible sunset reflection      | Good match      |
| Camera Motion        | Slow movement                  | Slow smooth movement           | Closely matched |
| Cloud Motion         | Gradual movement               | Gradual movement               | Good match      |
| Realism              | Photorealistic                 | Photorealistic                 | Good match      |
| Temporal Consistency | Stable                         | Mostly stable                  | Improved        |

---

# Step 10 – Identify Differences

### Observed Differences

1. The exact mountain shapes may not be identical.
2. The position of the sun may vary slightly.
3. The river width may differ from the original.
4. Some trees may appear in different positions.
5. Cloud formations may change.
6. Water reflections may not exactly match the original.
7. Camera movement may be slightly different.
8. Fine vegetation details may change between frames.

### Analysis

The generated video creates a new interpretation of the reference rather than reproducing every frame exactly. Therefore, minor differences in geometry, cloud patterns, vegetation, and motion can occur.

---

# Step 11 – Iterative Prompt Refinement

## Version 1 – Basic Prompt

> A serene landscape with mountains and a river during sunset.

### Result

A general mountain landscape was generated, but the composition and motion were not sufficiently similar to the reference.

---

## Version 2 – Detailed Prompt

> A serene mountain valley during sunset with snow-covered mountains, a calm river, green trees, colorful clouds, and warm golden sunlight reflecting on the water.

### Result

The major visual elements were generated correctly, but camera movement and environmental motion were limited.

---

## Version 3 – Motion-Enhanced Prompt

> A photorealistic mountain valley at sunset with a flowing river, moving clouds, gently moving trees, realistic water reflections, and a slow forward cinematic camera movement.

### Result

Motion and temporal consistency improved.

---

## Version 4 – Final Refined Prompt

> Create a high-resolution, photorealistic cinematic video closely matching the reference mountain landscape. Show a wide alpine valley during golden-hour sunset. A calm river flows continuously through the foreground with realistic ripples and reflections. Snow-covered mountains remain stable in the background. Evergreen trees and vegetation move gently in a light breeze. Purple, pink, orange, and golden clouds drift slowly across the sky. The low sun creates warm rays and a long golden reflection across the river. The camera slowly and smoothly moves forward along the river while maintaining a wide panoramic composition. Use realistic water physics, natural lighting, atmospheric depth, stable landscape geometry, smooth temporal consistency, and professional landscape cinematography. No people, buildings, vehicles, animals, text, logos, cartoon effects, sudden movements, camera shake, or object deformation.

### Result

The final version produces a more coherent, realistic, and visually similar video with improved camera movement, environmental motion, lighting, and temporal consistency.

---

# Step 12 – Evaluation of Prompting Techniques

| Prompting Technique   | Main Purpose              | Result                   |
| --------------------- | ------------------------- | ------------------------ |
| Simple Prompt         | Establish basic concept   | Basic landscape          |
| Detailed Prompt       | Add visual information    | Improved similarity      |
| Style Prompt          | Control visual appearance | More photorealistic      |
| Motion Prompt         | Control video movement    | Better temporal behavior |
| Negative Instructions | Remove unwanted elements  | Cleaner output           |
| Iterative Prompting   | Refine previous result    | Best overall output      |

---

# Step 13 – Complete Video Generation Workflow

```text
                  ORIGINAL / REFERENCE VIDEO
                            ↓
                     VIDEO ANALYSIS
                            ↓
                 IDENTIFY KEY ELEMENTS
                            ↓
                    INITIAL PROMPT
                            ↓
                 GENERATE INITIAL VIDEO
                            ↓
                   EVALUATE OUTPUT
                            ↓
                   DETAILED PROMPT
                            ↓
                     STYLE PROMPT
                            ↓
                     MOTION PROMPT
                            ↓
                   GENERATE VIDEO
                            ↓
               COMPARE WITH REFERENCE
                            ↓
                  IDENTIFY DIFFERENCES
                            ↓
                  ITERATIVE REFINEMENT
                            ↓
                FINAL REFINED PROMPT
                            ↓
                  GENERATE FINAL VIDEO
                            ↓
              FINAL VIDEO COMPARISON
```

---

# Step 14 – Final Comparison Report

## Original Video

The original video presents a realistic mountain landscape during sunset. It contains snow-covered mountains, a calm river, evergreen trees, colorful clouds, warm golden lighting, and slow cinematic camera movement.

## Initial Generated Video

The initial generated video successfully represents the general mountain landscape but has limited control over camera movement, environmental motion, composition, and temporal consistency.

## Final Generated Video

The final generated video reproduces the major characteristics of the reference more closely. It contains the mountain valley, river, vegetation, sunset, colorful clouds, realistic lighting, flowing water, drifting clouds, gentle vegetation movement, and smooth camera motion.

## Similarities

* Mountain valley
* Snow-covered mountains
* River
* Evergreen trees
* Sunset
* Warm golden lighting
* Colorful clouds
* River reflections
* Cinematic composition
* Slow camera movement

## Differences

* Mountain geometry
* Exact cloud formations
* Sun position
* River shape
* Vegetation arrangement
* Camera trajectory
* Fine environmental details

## Refinements Applied

The final prompt was improved by adding:

* Detailed landscape description
* Exact color information
* Lighting instructions
* Camera movement
* River movement
* Cloud movement
* Tree and grass movement
* Stable mountain geometry
* Realistic water physics
* Atmospheric perspective
* Temporal consistency
* Negative instructions

---

# Evaluation

The generated videos are evaluated using the following criteria:

| Criterion            | Description                             |
| -------------------- | --------------------------------------- |
| Visual Similarity    | Similarity to the reference video       |
| Motion Quality       | Smoothness and realism of movement      |
| Temporal Consistency | Stability of objects across frames      |
| Realism              | Photorealistic appearance               |
| Composition          | Similarity in framing and arrangement   |
| Prompt Effectiveness | Improvement achieved through refinement |

### Sample Evaluation

| Version              | Visual Similarity | Motion Quality | Realism   | Temporal Consistency |
| -------------------- | ----------------- | -------------- | --------- | -------------------- |
| Basic Prompt         | Moderate          | Low            | Good      | Moderate             |
| Detailed Prompt      | Good              | Moderate       | Very Good | Good                 |
| Motion Prompt        | Very Good         | Very Good      | Very Good | Very Good            |
| Final Refined Prompt | Excellent         | Very Good      | Excellent | Very Good            |

*The above ratings are sample qualitative observations for the experiment and should be replaced with actual observations if measured experimentally.*

---

# Instructions

1. Examine the given/reference video carefully.
2. Identify its objects, colors, lighting, composition, style, and motion.
3. Write a simple initial prompt.
4. Generate the initial video.
5. Record and evaluate the initial output.
6. Refine the prompt by adding visual details.
7. Add style and artistic instructions.
8. Add camera and environmental motion instructions.
9. Add negative instructions to prevent unwanted elements.
10. Generate the final video.
11. Compare the original, initial generated, and final generated videos.
12. Record the similarities and differences.
13. Refine the prompt iteratively if required.
14. Save the original video, generated videos, and prompts used.

---

# Deliverables

1. **Original / Reference Video** – Video provided for reference.
2. **Initial Generated Video** – Video generated using the initial prompt.
3. **Final Generated Video** – Video generated using the refined prompt.
4. **Prompts Used** – Basic, detailed, style, motion, and final prompts.
5. **Comparison Report** – Comparison between original, initial generated, and final generated videos.
6. **Iteration Record** – Documentation of changes made to the prompts.
7. **Evaluation** – Analysis of visual quality, motion consistency, realism, and similarity.

---

---

# Output 

1. **Sample video**


https://github.com/user-attachments/assets/fa620799-d910-4d3c-8faa-05c3fc44d412


2. **Final video**



https://github.com/user-attachments/assets/07162c9a-8ea1-4f48-b86d-f9ad81207736

---

# Conclusion

By using detailed and well-crafted prompts, text-to-video generation models can be used to reproduce the major visual and motion characteristics of an existing video.

The experiment demonstrated that starting with a simple prompt and progressively adding details about **objects, colors, lighting, composition, style, camera movement, environmental motion, and temporal consistency** improves the quality of the generated video.

The comparison between the initial and final generated videos shows that **iterative prompt refinement** can improve visual similarity, realism, motion quality, and consistency. Video prompting requires additional instructions about movement and temporal behavior compared with image prompting.

Thus, carefully designed prompts can significantly improve AI-generated videos and can be applied to creative, educational, engineering, simulation, visualization, and other practical applications.

# Result

The exploration of prompting techniques for video generation was successfully performed. The reference video was analyzed, an initial video was generated using a basic prompt, and the prompt was progressively refined using detailed, style, motion, and iterative prompting techniques. A final video was generated and compared with the original video, demonstrating the effect of prompt refinement on video quality, realism, motion, and visual similarity.
