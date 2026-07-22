---
title: Template Library
description: Browse ready-made Firefly Graph templates you can open and adapt to your own project
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: yes
---
# 5. Template library

A quick-reference index of Firefly Graph templates, organized by what each one produces or does. Every example is a starting point — swap in your own brand, product, and prompts before using a template in production.

## Image generation & style

* [**Getting Started - Generate an image**](/help/firefly/graph/templates/get-started-gen-image.md) — This template is a basic graph: one prompt node into one generation node into one output. Use it as the first template to open with any brand new user.
* [**Consistent character generation**](/help/firefly/graph/templates/character-gen.md) — In this graph template you load one reference image of a character, then swap the scene or pose prompt for each new shot. The character reference stays locked while the surrounding scene changes.
* [**Style extraction**](/help/firefly/graph/templates/style-extraction.md) — In this graph template you feed in a reference image to extract its color, light, and texture treatment. You can then apply that treatment to any new image run through the same graph.
* [**Sunset vibes**](/help/firefly/graph/templates/sunset-vibes.md) — In this graph template you can create a 3D typographic image from a text prompt. The template handles placement and color balance automatically.

## Segmentation & compositing

* [**Getting Started - Segment an image**](/help/firefly/graph/templates/get-started-segment-image.md) — In this graph template you load any source image and run the segmentation node to isolate the subject from its background. Pair with a background replacement node for a clean cutout.
* [**Composite and blend layers**](/help/firefly/graph/templates/composite-blend-layers.md) — In this graph template you stack a product cutout and a background scene as separate layer inputs. Adjust blend mode and lighting nodes until the composite reads as one shot.
* [**Selective color correction**](/help/firefly/graph/templates/selective-color-correction.md) — In this graph template you mask a specific region that needs correction and set the target color on that node only. The rest of the image passes through the graph untouched.

## Video & motion

* [**Getting Started - Video generation**](/help/firefly/graph/templates/get-started-video-gen.md) — In this graph template you feed in an approved still key art and a short motion prompt. The template generates a video cut built from that same key art rather than a new shoot.
* [**Bullet Time VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) — In this graph template, you feed a hero product or subject image to generate a rotating sequence of angles around it, then stitch the freeze frame sweep automatically.

## Storyboarding

* [**Text to storyboard**](/help/firefly/graph/templates/text-to-storyboard.md) — In this graph template you replace text input nodes with elements from your story. Each line becomes its own storyboard frame, generated in sequence and laid out for review as a single panel set.
* [**Storyboard builder**](/help/firefly/graph/templates/storyboard-builder.md) — In this graph template you build a storyboard scene by scene, adding one node per beat of the narrative. Reorder nodes to test a different sequence before locking the final panel order.

## 3D & Character

* [**Real time shaders**](/help/firefly/graph/templates/real-time-shaders.md) — In this graph template you start with an image and apply three different custom shaders and preview the result in real time. Adjust shader parameters directly on the node rather than re-rendering from scratch.
* [**Character model generation**](/help/firefly/graph/templates/character-model-generation.md) — In this graph template you create a 3D animated style of an illustration. The template generates a base 3D model pass ready to hand to a modeler for cleanup, rather than starting from a blank scene.
* [**Vinyl toy design**](/help/firefly/graph/templates/vinyl-toy-design.md) — In this graph template you input a character or mascot reference, and render it in a stylized vinyl toy form. There are turnaround angles for a licensing or product review deck.
* [**Sketch to 3D turnaround**](/help/firefly/graph/templates/sketch-to-3d.md) — In this graph template you turn a sketch into a 3D character. The graph builds a rotating 3D turnaround from it, ready for an internal design review before any physical prototype.

## Product & Brand Mockups

* [**Branding visualization**](/help/firefly/graph/templates/branding-visualization.md) — In this graph template learn how to visualize product scenes. Feed in brand guidelines or a logo and color palette and the graph outputs both static key art and a short motion pass in one run, so both formats stay visually aligned.
* [**Brand product mockup**](/help/firefly/graph/templates/brand-product-mockup.md) — In this graph template learn how to visualize your product in differen scenes. You drop a product render or photo into the mockup node and the graph places it inside a fully branded scene, with lighting and shadow matched to that scene automatically.
* [**Editorial photoshoot**](/help/firefly/graph/templates/editorial-photoshoot.md) — In this graph template you load a model reference and swap the garment input for each new look. Pose and lighting nodes stay locked across the set for a consistent editorial feel.
* [**Photography studio**](/help/firefly/graph/templates/photography-studio.md) — In this graph template you place a product render on the studio backdrop and adjust the lighting until the result reads like a real studio capture.
* [**Apply decal to surfaces**](/help/firefly/graph/templates/decal-to-surfaces.md) — In this graph template you load the base product mockup and the decal or logo asset as separate inputs. The template wraps the decal onto the surface geometry so it follows contours correctly.

## Batch & Consistency Operations

* [**Design system generator**](/help/firefly/graph/templates/design-system-generator.md) — In this graph template you generate a design system based on a website screenshot. The graph produces a matching set of icons, patterns, and layout components in a single batch run.
* [**Headshots generation**](/help/firefly/graph/templates/headshots-generation.md) — In this graph template you harmonize a batch of corporate headshots. Load the source photos, one per person, and the graph normalizes lighting, background, and crop across the whole set in one run.

Return to [Get started with Firefly Graph](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph).