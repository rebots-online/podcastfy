# Podcastfy
[![CodeFactor](https://www.codefactor.io/repository/github/souzatharsis/podcastfy/badge)](https://www.codefactor.io/repository/github/souzatharsis/podcastfy)
[![Issues](https://img.shields.io/github/issues-raw/souzatharsis/podcastfy)](https://github.com/souzatharsis/podcsatfy/issues)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Podcastfy: Your GenAI-Powered Companion for Transforming Multi-Source Text into Captivating Audio Conversations

Podcastfy is an LLM-based Python package and CLI tool that enables programatic creation of engaging audio podcasts from web content and text sources. Unlike tools focused primarily on note-taking or research synthesis (e.g. NotebookLM ❤️), Podcastfy specializes and focuses solely on the programatic generation of engaging, conversational audio from a multitude of text sources.

Ideal for Developers that build data-driven products for creators, educators, and researchers seeking to transform written information into easily digestible audio content. Podcastfy offers a unique solution for bridging the gap between text and audio consumption, programatically.

## Features

- Generate engaging, AI-powered conversational content from multiple sources (URLs and PDFs)
- Create high-quality transcripts from diverse textual information sources
- Convert pre-existing transcript files into dynamic podcast episodes
- Support for multiple advanced text-to-speech models (OpenAI and ElevenLabs) for natural-sounding audio
- Support for multiple languages, enabling global content creation
- Seamlessly integrate CLI for streamlined workflows


## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/podcastfy.git
   cd podcastfy
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

- [Python Package](usage/podcastfy.ipynb)

- [CLI](usage/cli.md)


    

## Configuration

The project uses a combination of a `.env` file for managing API keys and sensitive information, and a `config.yaml` file for non-sensitive configuration settings. Follow these steps to set up your configuration:

1. Create a `.env` file in the root directory of the project.
2. Add your API keys and other sensitive information to the `.env` file. For example:

   ```
   JINA_API_KEY=your_jina_api_key_here
   GEMINI_API_KEY=your_gemini_api_key_here
   ELEVENLABS_API_KEY=your_elevenlabs_api_key_here
   OPENAI_API_KEY=your_openai_api_key_here
   ```

3. The `config.yaml` file in the root directory contains non-sensitive configuration settings. You can modify this file to adjust various parameters such as output directories, text-to-speech settings, and content generation options.

The application will automatically load the environment variables from `.env` and the configuration settings from `config.yaml` when it runs.

Note: Never share your `.env` file or commit it to version control. It contains sensitive information that should be kept private. The `config.yaml` file can be shared and version-controlled as it doesn't contain sensitive data.

See [Configuration](usage/config.md) if you would like to further customize settings.

## Example Use Cases

1. Content Summarization: Busy professionals can stay informed on industry trends by listening to concise audio summaries of multiple articles, saving time and gaining knowledge efficiently.
2. Language Localization: Non-native English speakers can access English content in their preferred language, breaking down language barriers and expanding access to global information.
3. Website Content Marketing: Companies can increase engagement by repurposing written website content into audio format, providing visitors with the option to read or listen.
4. Personal Branding: Job seekers can create unique audio-based personal presentations from their CV or LinkedIn profile, making a memorable impression on potential employers.
5. Research Paper Summaries: Graduate students and researchers can quickly review multiple academic papers by listening to concise audio summaries, speeding up the research process.
6. Long-form Podcast Summarization: Podcast enthusiasts with limited time can stay updated on their favorite shows by listening to condensed versions of lengthy episodes.
7. News Briefings: Commuters can stay informed about daily news during travel time with personalized audio news briefings compiled from their preferred sources.
8. Educational Content Creation: Educators can enhance learning accessibility by providing audio versions of course materials, catering to students with different learning styles.
9. Book Summaries: Avid readers can preview books efficiently through audio summaries, helping them make informed decisions about which books to read in full.
10. Conference and Event Recaps: Professionals can stay updated on important industry events they couldn't attend by listening to audio recaps of conference highlights and key takeaways.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Disclaimer

This tool is designed for personal or educational use. Please ensure you have the necessary rights or permissions before using content from external sources for podcast creation. All audio content is AI-generated and it is not intended to clone real-life humans!