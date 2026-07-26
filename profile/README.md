<p align="center">
  <img alt="CUT3" src="https://raw.githubusercontent.com/Crypto-Communism/.github/main/camera.png"/>
</p>

# CUT3 - a vibe-coding IDE for video editing and generation

Available at [cut3.ai](https://cut3.ai).

## Agents

The system is organised as several agents with separate responsibilities rather than a single model handling the whole request.

**Director.** Plans the video and reviews the result. It determines the structure, the pacing and the length of each shot, decides which material from the researcher is used, and rejects work that does not fit the plan.

**Researcher.** Collects the material. It reads the source, works out the angle, writes the script, and gathers the footage, images and audio needed to support it.

**Editor.** Assembles the timeline. It places the cuts, applies transitions and effects, sets the colour treatment, adds sound effects, and animates the text and subtitles.

## Live preview

The video is previewed as it is being assembled, without a full render. Instructions can be given while the agents are working: a scene can be removed, the pacing of a section changed, or a shot replaced, and the preview updates to reflect the change. This removes the render step from the editing loop.
