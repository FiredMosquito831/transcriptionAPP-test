# Hi this is a test for my transcription app (english only)

### I made a smaller version that does english only transcriptionsn with speaker diarization and audio denoising (the WEB UI is made with Gradio)

#### You can try out and test the app for free(english only) by pressing the button below:


<a href="https://a919-2a02-2f09-d20e-6200-341e-66a6-7af3-f403.ngrok-free.app">
  <button>Test my app</button>
</a>

## This is what the real app looks like:

![image](https://cdn.discordapp.com/attachments/665903443998932992/1298737404584267867/image.png?ex=671b4fb6&is=6719fe36&hm=2ed6ae47e04cc1b05b6871d09b0a8d54b0345d8617487cfc0fe25e0523f3d5f4&)

### It can:

- [X] Transcription and diarization
- [X] Audio pre-processing (denoising)
- [X] Save transcription and diarization as 2 different text files
- [X] Process full folders
- [ ] Have a progress bar 
- [ ] Use a language model for audio post-processing to improve accuracy (will do)
- [ ] Use another model for summarization and data extraction as another option

### Some details:  WORK IN PROGRESS (need to correct them)

| Model           | Size (GB) | VRAM Requirements | RAM Requirements | Supported Languages                                                                                                                      | Speed           |
|-----------------|-----------|-------------------|------------------|------------------------------------------------------------------------------------------------------------------------------------------|-----------------|
| Tiny        | 0.07      | ~1 GB            | ~2 GB           | Primarily English; limited support for Spanish, French, German, Italian, Portuguese, Dutch, Russian, Japanese, Korean                          | Fastest         |
| Tiny.en     | 0.07      | ~1 GB            | ~2 GB           | English only                                                                                                                                   | Fastest         |
| Base        | 0.14      | ~1.2 GB          | ~2.5 GB         | Supports 14 languages: English, Spanish, French, German, Italian, Portuguese, Dutch, Russian, Japanese, Korean, and a few others               | Very Fast       |
| Base.en     | 0.14      | ~1.2 GB          | ~2.5 GB         | English only                                                                                                                                   | Very Fast       |
| Small       | 0.46      | ~2.4 GB          | ~3-4 GB         | Expanded language support: covers over 50 languages, including European and Asian languages                                                    | Fast            |
| Medium      | 1.5       | ~5 GB            | ~8 GB           | Full language support with 57 languages covering major languages plus Polish, Swedish, Thai, Ukrainian, Czech, Vietnamese, Hebrew, Indonesian  | Moderate        |
| Medium.en   | 1.5       | ~5 GB            | ~8 GB           | English only                                                                                                                                   | Moderate        |
| Large       | 2.9       | ~10-12 GB        | ~12-16 GB       | Comprehensive support for 57 languages, including low-resource languages like Nepali, Somali, Swahili, Urdu, Tagalog, Croatian, and more       | Slower          |
| Large-v2 / Turbo | 3.5-4 | ~12-14 GB       | ~16 GB          | Same as Large; optimized for lower latency across all supported languages                                                                      | Fast (Optimized)|

