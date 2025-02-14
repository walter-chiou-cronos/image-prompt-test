# Tweet

Unlocking financial powers like a true shonen hero means knowing your assets and wielding them wisely! 💪✨ Build your portfolio like a well-rounded anime squad—balance is key! 🎮💖

## Prompt Template

```
# TASK: You are an expert image prompt engineer. Your goal is to generate a comprehensive image prompt for DALL-E.

# Tweet Content:
Franklin Templeton is extending its FOBXX fund to Solana!  This is a game-changer for blockchain adoption!  Dive into new DeFi opportunities and keep an eye on the growth potential! 🚀

# Extractable Variables from [Tweet Content]
- [Subject]: Identify the main subject.
- [Environment]: Extract the setting or background context.
- [Emotion]: Capture the underlying emotion or feeling expressed in the tweet.
- [Mood]: Note any adjectives or tone that set the overall atmosphere.

# Art Style
{{ArtStyle}}

# Detail Level
{{DetailLevel}}

# Things to avoid
- Avoid creating LOGOs or symbols
- Avoid showing numbers or text on the image

Instructions:
1. Analyze the tweet to extract the [Subject], [Environment], [Emotion], and [Mood] and use these elements to describe the image.
2. Incorporate the provided [Art Style] and [Detail Level].
3. Combine these elements into a cohesive description that DALL-E can use to generate an image.

# Task:
Generate the final prompt as a detailed paragraph.

Your response must be formatted as a JSON block with this structure:
\`\`\`json
{
  "subject": <string>,
  "environment": <string>,
  "emotion": <string>,
  "mood": <string>,
  "prompt" <string>
}
\`\`\`
```

# Variables

```typescript
export const ART_STYLES = {
  DIGITAL_ILLUSTRATION:
    "Digital Illustration: Modern style using digital tools with clean lines and vibrant colors.",
  ANIME:
    "Anime: Stylized Japanese animation style with large eyes and expressive features.",
  WATERCOLOR:
    "Watercolor: Soft, blended colors mimicking traditional watercolor techniques.",
  PENCIL_SKETCH:
    "Pencil Sketch: Hand-drawn appearance with visible pencil strokes and detailed line work.",
  "3D_RENDER":
    "3D Render: Computer-generated imagery with realistic lighting and depth.",
  CYBERPUNK:
    "Cyberpunk: Futuristic style with neon accents, high-tech elements, and urban grit.",
  MINIMALIST:
    "Minimalist: Simplified design focusing on clean lines and limited color palettes.",
} as const;

export const DETAIL_LEVEL = {
  HIGH_DETAIL:
    "High Detail: Intricate details with fine resolution throughout the image.",
  MINIMAL_DETAIL:
    "Minimal Detail: A simplified representation with very few elements.",
  SIMPLIFIED: "Simplified: Details are reduced to emphasize key elements only.",
  FINE_LINE: "Fine-Line: Delicate, precise lines that define the image.",
  STYLIZED:
    "Stylized: Artistic interpretation with exaggerated or simplified details.",
} as const;
```

# Results

```json
[
  {
    "artStyle": "DIGITAL_ILLUSTRATION",
    "detailLevel": "HIGH_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-HIGH_DETAIL.png"
  },
  {
    "artStyle": "DIGITAL_ILLUSTRATION",
    "detailLevel": "MINIMAL_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-MINIMAL_DETAIL.png"
  },
  {
    "artStyle": "DIGITAL_ILLUSTRATION",
    "detailLevel": "SIMPLIFIED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-SIMPLIFIED.png"
  },
  {
    "artStyle": "DIGITAL_ILLUSTRATION",
    "detailLevel": "FINE_LINE",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-FINE_LINE.png"
  },
  {
    "artStyle": "DIGITAL_ILLUSTRATION",
    "detailLevel": "STYLIZED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-STYLIZED.png"
  },
  {
    "artStyle": "ANIME",
    "detailLevel": "HIGH_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-HIGH_DETAIL.png"
  },
  {
    "artStyle": "ANIME",
    "detailLevel": "MINIMAL_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-MINIMAL_DETAIL.png"
  },
  {
    "artStyle": "ANIME",
    "detailLevel": "SIMPLIFIED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-SIMPLIFIED.png"
  },
  {
    "artStyle": "ANIME",
    "detailLevel": "FINE_LINE",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-FINE_LINE.png"
  },
  {
    "artStyle": "ANIME",
    "detailLevel": "STYLIZED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-STYLIZED.png"
  },
  {
    "artStyle": "WATERCOLOR",
    "detailLevel": "HIGH_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-HIGH_DETAIL.png"
  },
  {
    "artStyle": "WATERCOLOR",
    "detailLevel": "MINIMAL_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-MINIMAL_DETAIL.png"
  },
  {
    "artStyle": "WATERCOLOR",
    "detailLevel": "SIMPLIFIED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-SIMPLIFIED.png"
  },
  {
    "artStyle": "WATERCOLOR",
    "detailLevel": "FINE_LINE",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-FINE_LINE.png"
  },
  {
    "artStyle": "WATERCOLOR",
    "detailLevel": "STYLIZED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-STYLIZED.png"
  },
  {
    "artStyle": "PENCIL_SKETCH",
    "detailLevel": "HIGH_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-HIGH_DETAIL.png"
  },
  {
    "artStyle": "PENCIL_SKETCH",
    "detailLevel": "MINIMAL_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-MINIMAL_DETAIL.png"
  },
  {
    "artStyle": "PENCIL_SKETCH",
    "detailLevel": "SIMPLIFIED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-SIMPLIFIED.png"
  },
  {
    "artStyle": "PENCIL_SKETCH",
    "detailLevel": "FINE_LINE",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-FINE_LINE.png"
  },
  {
    "artStyle": "PENCIL_SKETCH",
    "detailLevel": "STYLIZED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-STYLIZED.png"
  },
  {
    "artStyle": "3D_RENDER",
    "detailLevel": "HIGH_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-HIGH_DETAIL.png"
  },
  {
    "artStyle": "3D_RENDER",
    "detailLevel": "MINIMAL_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-MINIMAL_DETAIL.png"
  },
  {
    "artStyle": "3D_RENDER",
    "detailLevel": "SIMPLIFIED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-SIMPLIFIED.png"
  },
  {
    "artStyle": "3D_RENDER",
    "detailLevel": "FINE_LINE",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-FINE_LINE.png"
  },
  {
    "artStyle": "3D_RENDER",
    "detailLevel": "STYLIZED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-STYLIZED.png"
  },
  {
    "artStyle": "CYBERPUNK",
    "detailLevel": "HIGH_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-HIGH_DETAIL.png"
  },
  {
    "artStyle": "CYBERPUNK",
    "detailLevel": "MINIMAL_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-MINIMAL_DETAIL.png"
  },
  {
    "artStyle": "CYBERPUNK",
    "detailLevel": "SIMPLIFIED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-SIMPLIFIED.png"
  },
  {
    "artStyle": "CYBERPUNK",
    "detailLevel": "FINE_LINE",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-FINE_LINE.png"
  },
  {
    "artStyle": "CYBERPUNK",
    "detailLevel": "STYLIZED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-STYLIZED.png"
  },
  {
    "artStyle": "MINIMALIST",
    "detailLevel": "HIGH_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-HIGH_DETAIL.png"
  },
  {
    "artStyle": "MINIMALIST",
    "detailLevel": "MINIMAL_DETAIL",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-MINIMAL_DETAIL.png"
  },
  {
    "artStyle": "MINIMALIST",
    "detailLevel": "SIMPLIFIED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-SIMPLIFIED.png"
  },
  {
    "artStyle": "MINIMALIST",
    "detailLevel": "FINE_LINE",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-FINE_LINE.png"
  },
  {
    "artStyle": "MINIMALIST",
    "detailLevel": "STYLIZED",
    "fileName": "./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-STYLIZED.png"
  }
]
```

### Image: DIGITAL_ILLUSTRATION-HIGH_DETAIL

![DIGITAL_ILLUSTRATION-HIGH_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-HIGH_DETAIL.png)

### Image: DIGITAL_ILLUSTRATION-MINIMAL_DETAIL

![DIGITAL_ILLUSTRATION-MINIMAL_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-MINIMAL_DETAIL.png)

### Image: DIGITAL_ILLUSTRATION-SIMPLIFIED

![DIGITAL_ILLUSTRATION-SIMPLIFIED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-SIMPLIFIED.png)

### Image: DIGITAL_ILLUSTRATION-FINE_LINE

![DIGITAL_ILLUSTRATION-FINE_LINE](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-FINE_LINE.png)

### Image: DIGITAL_ILLUSTRATION-STYLIZED

![DIGITAL_ILLUSTRATION-STYLIZED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-DIGITAL_ILLUSTRATION-STYLIZED.png)

### Image: ANIME-HIGH_DETAIL

![ANIME-HIGH_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-HIGH_DETAIL.png)

### Image: ANIME-MINIMAL_DETAIL

![ANIME-MINIMAL_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-MINIMAL_DETAIL.png)

### Image: ANIME-SIMPLIFIED

![ANIME-SIMPLIFIED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-SIMPLIFIED.png)

### Image: ANIME-FINE_LINE

![ANIME-FINE_LINE](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-FINE_LINE.png)

### Image: ANIME-STYLIZED

![ANIME-STYLIZED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-ANIME-STYLIZED.png)

### Image: WATERCOLOR-HIGH_DETAIL

![WATERCOLOR-HIGH_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-HIGH_DETAIL.png)

### Image: WATERCOLOR-MINIMAL_DETAIL

![WATERCOLOR-MINIMAL_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-MINIMAL_DETAIL.png)

### Image: WATERCOLOR-SIMPLIFIED

![WATERCOLOR-SIMPLIFIED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-SIMPLIFIED.png)

### Image: WATERCOLOR-FINE_LINE

![WATERCOLOR-FINE_LINE](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-FINE_LINE.png)

### Image: WATERCOLOR-STYLIZED

![WATERCOLOR-STYLIZED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-WATERCOLOR-STYLIZED.png)

### Image: PENCIL_SKETCH-HIGH_DETAIL

![PENCIL_SKETCH-HIGH_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-HIGH_DETAIL.png)

### Image: PENCIL_SKETCH-MINIMAL_DETAIL

![PENCIL_SKETCH-MINIMAL_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-MINIMAL_DETAIL.png)

### Image: PENCIL_SKETCH-SIMPLIFIED

![PENCIL_SKETCH-SIMPLIFIED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-SIMPLIFIED.png)

### Image: PENCIL_SKETCH-FINE_LINE

![PENCIL_SKETCH-FINE_LINE](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-FINE_LINE.png)

### Image: PENCIL_SKETCH-STYLIZED

![PENCIL_SKETCH-STYLIZED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-PENCIL_SKETCH-STYLIZED.png)

### Image: 3D_RENDER-HIGH_DETAIL

![3D_RENDER-HIGH_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-HIGH_DETAIL.png)

### Image: 3D_RENDER-MINIMAL_DETAIL

![3D_RENDER-MINIMAL_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-MINIMAL_DETAIL.png)

### Image: 3D_RENDER-SIMPLIFIED

![3D_RENDER-SIMPLIFIED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-SIMPLIFIED.png)

### Image: 3D_RENDER-FINE_LINE

![3D_RENDER-FINE_LINE](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-FINE_LINE.png)

### Image: 3D_RENDER-STYLIZED

![3D_RENDER-STYLIZED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-3D_RENDER-STYLIZED.png)

### Image: CYBERPUNK-HIGH_DETAIL

![CYBERPUNK-HIGH_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-HIGH_DETAIL.png)

### Image: CYBERPUNK-MINIMAL_DETAIL

![CYBERPUNK-MINIMAL_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-MINIMAL_DETAIL.png)

### Image: CYBERPUNK-SIMPLIFIED

![CYBERPUNK-SIMPLIFIED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-SIMPLIFIED.png)

### Image: CYBERPUNK-FINE_LINE

![CYBERPUNK-FINE_LINE](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-FINE_LINE.png)

### Image: CYBERPUNK-STYLIZED

![CYBERPUNK-STYLIZED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-CYBERPUNK-STYLIZED.png)

### Image: MINIMALIST-HIGH_DETAIL

![MINIMALIST-HIGH_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-HIGH_DETAIL.png)

### Image: MINIMALIST-MINIMAL_DETAIL

![MINIMALIST-MINIMAL_DETAIL](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-MINIMAL_DETAIL.png)

### Image: MINIMALIST-SIMPLIFIED

![MINIMALIST-SIMPLIFIED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-SIMPLIFIED.png)

### Image: MINIMALIST-FINE_LINE

![MINIMALIST-FINE_LINE](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-FINE_LINE.png)

### Image: MINIMALIST-STYLIZED

![MINIMALIST-STYLIZED](./tweet-image-2c47a62a-7f2d-0b43-a1fd-c7253950cbfa-MINIMALIST-STYLIZED.png)
