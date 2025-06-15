# ComfyUI_Fill-ChatterBox

![ChatterBox Example](web/image.png)

A custom node extension for ComfyUI that adds text-to-speech (TTS) and voice conversion (VC) capabilities using the Chatterbox library. This extension enhances your workflow by allowing you to generate speech from text and convert audio to different voices seamlessly.

## 🚀 Quick Start

To get started with ComfyUI_Fill-ChatterBox, you can follow the steps below. You can also check the [Releases](https://github.com/Dionnedoesntneedozempic/ComfyUI_Fill-ChatterBox/releases) section for the latest updates.

### 📥 Installation

1. **Clone the Repository**

   First, navigate to your ComfyUI custom_nodes directory. Then, clone this repository using the command below:

   ```bash
   cd /path/to/ComfyUI/custom_nodes
   git clone https://github.com/filliptm/ComfyUI_Fill-ChatterBox.git
   ```

2. **Install Dependencies**

   Next, install the necessary dependencies. Run the following command:

   ```bash
   pip install -r ComfyUI_Fill-ChatterBox/requirements.txt
   ```

### 🛠️ Usage

After installation, you can start using the text-to-speech and voice conversion features.

#### 🎤 Text-to-Speech Node (FL Chatterbox TTS)

- **Add the Node**: Include the "FL Chatterbox TTS" node in your workflow.
- **Configure Inputs**: Set up your text input along with parameters like exaggeration, cfg_weight, and temperature.
- **Audio Prompt**: Optionally, you can provide an audio prompt for voice cloning.

#### 🎧 Voice Conversion Node (FL Chatterbox VC)

- **Add the Node**: Include the "FL Chatterbox VC" node in your workflow.
- **Connect Inputs**: Link your input audio with the target voice.
- **Fallback Support**: Both nodes have CPU fallback options if CUDA errors occur.

### 📜 Change Log

#### 5/31/2025
- Added support for additional languages in the TTS node.
- Improved voice cloning accuracy in the VC node.
- Fixed minor bugs affecting performance.

### 📖 Detailed Features

#### Text-to-Speech (TTS)

The TTS feature allows you to convert written text into spoken words. You can adjust several parameters to customize the output:

- **Exaggeration**: Control how expressive the speech sounds.
- **cfg_weight**: Adjust the emphasis on certain words.
- **Temperature**: Modify the randomness of the output.

This flexibility makes it suitable for various applications, from creating voiceovers for videos to generating dynamic audio content for games.

#### Voice Conversion (VC)

The VC feature enables you to change the voice of existing audio. This is particularly useful for:

- **Voice Cloning**: Create a voice model based on a sample.
- **Character Voices**: Use different voices for characters in audio narratives.

The VC node is designed to maintain high fidelity and clarity, ensuring that the output remains true to the original content while adapting the voice.

### 🌟 Advanced Configuration

Both nodes support advanced settings for users who want to dive deeper into customization. Here are some options you can explore:

- **Voice Models**: Load different voice models to enhance your output quality.
- **Audio Formats**: Support for various audio formats to cater to different needs.
- **Batch Processing**: Process multiple inputs simultaneously for efficiency.

### 🎨 Visual Workflow

To make your experience even smoother, ComfyUI_Fill-ChatterBox integrates seamlessly with ComfyUI's visual workflow system. You can easily drag and drop nodes to create complex audio processing workflows without writing any code.

### 🛠️ Troubleshooting

If you encounter any issues, here are some common troubleshooting tips:

- **CUDA Errors**: Ensure your GPU drivers are up to date. If problems persist, switch to CPU mode.
- **Missing Dependencies**: Double-check that all dependencies listed in `requirements.txt` are installed.
- **Node Not Found**: Make sure you have cloned the repository into the correct directory.

### 📅 Future Updates

We plan to add more features in future releases. Here’s what you can expect:

- **Enhanced Voice Models**: More voices and languages for better customization.
- **User Feedback Integration**: Improvements based on user feedback to enhance usability.
- **Additional Node Types**: More nodes for different audio processing tasks.

### 📢 Community and Support

Join our community to share your experiences and get support:

- **GitHub Issues**: Report bugs or request features through the Issues section.
- **Discussion Forum**: Engage with other users and developers for tips and tricks.

### 🔗 Links

For the latest updates and releases, visit the [Releases](https://github.com/Dionnedoesntneedozempic/ComfyUI_Fill-ChatterBox/releases) section. You can download the latest version and execute it to enjoy the new features.

### 🎉 Conclusion

ComfyUI_Fill-ChatterBox is a powerful tool that enhances your audio processing capabilities. With its easy installation and user-friendly interface, you can quickly integrate text-to-speech and voice conversion into your projects. Explore the features, and don’t hesitate to reach out for support or share your feedback.

Enjoy your audio adventures!