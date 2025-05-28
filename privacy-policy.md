<a href="index.html">Go to Home Page</a>
<a href="terms-of-service.html">Terms of Service</a>
# Privacy Policy for Socials Automator

**Last Updated: May 28, 2025**

Socials Automator ("us", "we", or "our") operates the Socials Automator application (the "Service"). This page informs you of our policies regarding the collection, use, and disclosure of personal data when you use our Service and the choices you have associated with that data.

This Privacy Policy is intended to help you understand what data we collect, why we collect it, and what we do with it, particularly in the context of requirements for using APIs such as the TikTok API.

## 1. Information Collection and Use
Socials Automator is primarily a tool that you run locally on your own system. As such, **we, the developers of Socials Automator, do not directly collect or store your personal data through the application's core operation.** The application interacts with various third-party services based on the configurations and credentials you provide.

### Data You Provide or Process:
- **API Keys and Credentials:** To function, the Application requires you to provide API keys, access tokens, client secrets, and other credentials for services like Reddit, YouTube, TikTok, Instagram, and potentially others (e.g., Ollama if run as a remote service). These credentials are typically stored locally on your system in configuration files (e.g., `config/*.json`) as managed by you. We strongly recommend securing these files and not sharing them.
- **Content Data:** The Application processes data from Reddit (stories, comments) and generates video content. This includes text, and potentially associated metadata from Reddit.
- **Configuration Data:** Settings for video generation, scheduling, and other operational parameters are stored in local configuration files.

### Data Processed by Third-Party Services:
When you use the Application to interact with third-party services, those services will process your data according to their own privacy policies:
- **Reddit:** When fetching stories, Reddit's API will be accessed. Refer to Reddit's Privacy Policy.
- **YouTube, TikTok, Instagram:** When uploading videos, these platforms will process the video content, titles, descriptions, tags, and your account information. Refer to their respective Privacy Policies (YouTube/Google, TikTok, Instagram/Meta).
- **Ollama (or other AI models):** If you use a local or remote AI model for metadata generation, the text content of stories will be sent to this model. If using a remote service, refer to its privacy policy.
- **Edge TTS, Whisper (or other TTS/STT services):** Story text is processed by these services to generate audio and subtitles. If these are cloud-based services you've configured, refer to their privacy policies.
- **Pexels or other video download sources:** The application may download background videos from sources you configure.

## 2. How Data is Handled by the Application
- **Local Storage:** Most data, including your credentials and configuration, is stored locally on the system where you run the Application.
- **No Central Server (by default for core application):** The core Socials Automator application, as described, is designed to run locally without transmitting your specific API keys or detailed processed content to a central server operated by the developers of Socials Automator.
- **Log Files:** The application generates local log files (`logs/*.log`) for operational monitoring and debugging. These logs may contain information about the processes run, story IDs, and errors, but are stored locally on your system.

## 3. Purpose of Data Processing (by the Application on your behalf)
The Application processes data solely for the purpose of:
- Fetching stories from Reddit based on your criteria.
- Generating video content by combining text, audio (TTS), subtitles (STT), and background videos.
- Generating metadata (titles, descriptions) for the videos.
- Uploading the generated videos to your specified social media accounts (YouTube, TikTok, Instagram).
- Scheduling these posts according to your configuration.

## 4. Data Security
You are responsible for the security of the system where Socials Automator is run and for the security of your API keys and credentials. We recommend:
- Storing credential files securely.
- Using strong, unique passwords/keys for all connected services.
- Keeping your system and software up to date.

## 5. Data Sharing and Disclosure
**We, the developers of Socials Automator, do not share your personal data or the specific content you process with any third parties, as we do not collect it centrally.**

Any sharing of data occurs directly between the Application (running on your system) and the third-party services you have configured it to use (e.g., uploading a video to your TikTok account shares that video with TikTok).

## 6. Your Data Rights
Since the data is primarily stored and managed locally by you, you have direct control over it. You can:
- Access, modify, or delete your configuration files and credentials.
- Access or delete locally stored log files.
- Manage content on the third-party platforms directly through their interfaces.

## 7. Children's Privacy
Our Service is not intended for use by children under the age of 13 (or a higher age if stipulated by local laws). We do not knowingly collect personally identifiable information from children.

## 8. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date.
You are advised to review this Privacy Policy periodically for any changes.

## 9. Contact Us
If you have any questions about this Privacy Policy, please contact us at [Your Contact Email or Method].

## For TikTok API Verification Purposes:
This application, Socials Automator, acts as a client on your local system to interact with various APIs, including potentially the TikTok API, at your direction and using credentials you provide. The application facilitates the creation and upload of video content. All data processing related to your TikTok account (uploads, content management) is performed by your local instance of the application interacting directly with the TikTok API, governed by TikTok's Terms of Service and Privacy Policy. The developers of Socials Automator do not have access to your TikTok account or data.
