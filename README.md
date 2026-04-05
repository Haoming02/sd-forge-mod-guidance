# SD Forge Mod Guidance
This is an Extension for [Forge Neo](https://github.com/Haoming02/sd-webui-forge-classic), which uses the good ol' **Clip** text encoder again for [Anima](https://huggingface.co/circlestone-labs/Anima) *(see [References](#references) for what this does)*

### Example

<table>
  <tr>
    <th>Off</th>
    <th>On</th>
  </tr>
  <tr>
    <td><img src="./before.webp" width="384"></td>
    <td><img src="./after.webp" width="384"></td>
  </tr>
</table>

- **Infotext**

```
masterpiece, best quality, good quality, absurdres, newest, safe,
1girl, solo, hatsune miku, vocaloid, casual, looking at viewer, smile, simple background, gradient background
Negative prompt: score_1, score_2, score_3, blurry, jpeg artifacts, sepia, watermark, worst quality, low quality, large breasts, muscular, deformed hands, bad anatomy, extra limbs, poorly drawn face, mutated, extra eyes, bad proportions, character doll, chibi, old, early, censored, 3d, high contrast, ai-generated
Steps: 30, Sampler: Euler a, Schedule type: Normal, CFG scale: 5, Seed: 1234, Size: 896x1152, Model hash: f5d9cad635, Model: animayume_v03, Clip skip: 2, RNG: CPU, Version: neo, Module 1: qwen_3_06b, Module 2: qwen_image_vae
```

- **Clip L:** https://huggingface.co/Anzhc/Noobai11-CLIP-L-and-BigG-Anime-Text-Encoders/tree/main

<hr>

#### References

- https://github.com/Anzhc/Anima-Mod-Guidance-ComfyUI-Node
- https://github.com/quickjkee/modulation-guidance
