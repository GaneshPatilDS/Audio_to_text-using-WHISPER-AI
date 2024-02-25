# Whisper - AI-Powered Audio Transcription 🎙️🔍

![Whisper Logo](https://github.com/openai/whisper/raw/main/docs/images/whisper_logo_dark_background.png)

Whisper is an AI-powered audio transcription tool developed by OpenAI. It utilizes state-of-the-art technology to transcribe spoken words from audio files accurately. With the ability to process various languages and accents, Whisper offers a powerful solution for converting spoken content into text.

## Installation

To install Whisper, use the following pip command:

```bash
!pip install git+https://github.com/openai/whisper.git
```

Additionally, ensure you have FFmpeg installed:

```bash
!sudo apt update && sudo apt install ffmpeg
```

## Usage

To transcribe an audio file using Whisper, you can use the following command:

```bash
!whisper "input_audio_file.wav" --model medium.en
```

Replace `"input_audio_file.wav"` with the path to your audio file and adjust the `--model` parameter based on your language and desired transcription quality.

## Example

Here is a sample command and output using Whisper:

```bash
!whisper "harvard.wav" --model medium.en
```

```
[00:00.000 --> 00:04.000] The stale smell of old beer lingers.
[00:04.000 --> 00:07.000] It takes heat to bring out the odor.
[00:07.000 --> 00:10.000] A cold dip restores health and zest.
[00:10.000 --> 00:12.000] A salt pickle tastes fine with ham.
[00:12.000 --> 00:15.000] Tacos al pastor are my favorite.
[00:15.000 --> 00:18.000] A zestful food is the hot cross bun.
```

## Acknowledgments

Special thanks to OpenAI for providing the Whisper tool for audio transcription.

For more details and advanced usage, refer to the [official Whisper repository](https://github.com/openai/whisper).

Enjoy transcribing your audio effortlessly with Whisper! 🎙️🔍
