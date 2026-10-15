# MindHelper: Closed-Loop Embodied Mental-State Reasoning for Precision Intervention

Project page for **MindHelper / MindClaw**.

Ruoxuan Zhang, Zhengguang Wang, Qiaoqiao Wan, Chenghao Yu, Hongxia Xie, Wen-Huang Cheng, Jianlong Fu
Jilin University · National Taiwan University · Microsoft Asia

![Precise intervention: keep silent until help is needed, then act](assets/precision.gif)

## Page contents

1. **What is precise intervention?** A short film (`assets/precision.mp4`) explaining when to keep silent and when to intervene.
2. **MindHelper Benchmark**: 590 examples across VirtualHome and ThreeDWorld.
3. **MindClaw**: framework overview.
4. **Experiments**: Table III.
5. **Model Comparison**: flow chart built from Fig. 7.
6. **Example**: an interactive, step-by-step walkthrough (`annotated-examples.html`).

## Deploy with GitHub Pages

This is a static site with no build step and no external dependencies.

1. Push the contents of this folder to the root of a repository. `index.html` must be at the top level.
2. In the repository, open **Settings → Pages**. Under **Source**, choose *Deploy from a branch*, select `main` and `/ (root)`, then click **Save**.
3. The site is published at `https://<user>.github.io/<repo>/` after about a minute.

To preview locally, run `python -m http.server` and open `http://localhost:8000`. Videos and the embedded example need HTTP; opening the file directly via `file://` will not work.

## Notes

- Subtitles for the overview film are rendered by the page, not burned into the video. Edit them in `PRECISION_CUES` in `index.html`.
- The Inter font is bundled under the SIL Open Font License (`assets/fonts/OFL.txt`).
- The module states shown in the interactive example are illustrative annotations, not exported run logs.
