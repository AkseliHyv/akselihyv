<table>
<tr>
<td width="200" valign="top">
<img src="assets/perlis.jpg" width="180" alt="Alan J. Perlis">
</td>
<td valign="top">

*“I think that it’s extraordinarily important that we in computer science keep fun in computing. When it started out, it was an awful lot of fun. Of course, the paying customers got shafted every now and then, and after a while we began to take their complaints seriously. We began to feel as if we really were responsible for the successful, error-free perfect use of these machines. I don’t think we are. I think we’re responsible for stretching them, setting them off in new directions, and keeping fun in the house. I hope the field of computer science never loses its sense of fun. Above all, I hope we don’t become missionaries. Don’t feel as if you’re Bible salesmen. The world has too many of those already. What you know about computing other people will learn. Don’t feel as if the key to successful computing is only in your hands. What’s in your hands, I think and hope, is intelligence: the ability to see the machine as more than when you were first led up to it, that you can make it more.”*

</td>
</tr>
</table>

**Alan J. Perlis** (April 1, 1922 – February 7, 1990)

# Akseli Hyvönen

Software developer studying at Metropolia, also going by axilian. I mostly build embedded things and tools around local language models: a handheld console written from scratch on an ESP32-S3, a heart rate monitor on a Pico W, and a chat app and a voice robot that run on models hosted on my own machines. I also make games, and lately I've been spending my weekends at hackathons.

You can find me at [akselihyv.com](https://akselihyv.com), on [LinkedIn](https://www.linkedin.com/in/akseli-hyv%C3%B6nen/), or at [akselihyv@gmail.com](mailto:akselihyv@gmail.com).

## Things I've been making

**[AkseLLM](https://github.com/AkseliHyv/aksellm)**\
A self-hosted web app for managing and chatting with local LLM configurations that run on [Ollama](https://ollama.com). Each configuration has its own parameters and system prompt, and responses stream in as Markdown, highlighted code and LaTeX. Runs as a single container.\
<sub>React, TypeScript, ASP.NET Core, Supabase, Docker. Complete.</sub>

**[Aceso](https://github.com/AkseliHyv/aceso)**\
MicroPython firmware for a heart rate variability monitor that measures through photoplethysmography, made in a team of three. It draws the live PPG waveform on an OLED display, computes HRV on the device, and sends measurements to Kubios over MQTT for further analysis.\
<sub>MicroPython, Raspberry Pi Pico W, MQTT. Complete.</sub>

**[AksBox](https://github.com/AkseliHyv/aksbox)**\
A handheld game console built from scratch around an ESP32-S3. The display driver, input handling, graphics, audio synthesis and game engine are all written for it, with no Arduino layer or graphics library. Currently a breadboard prototype.\
<sub>C, ESP-IDF, FreeRTOS. In progress.</sub>

**AksoBot**\
A voice robot that listens, thinks and talks back. It detects speech with a custom voice activity detector, transcribes it locally with Faster Whisper, answers with a local model on Ollama, and speaks through Edge TTS. Meant to eventually live inside a physical robot on a Raspberry Pi.\
<sub>Python, Faster Whisper, Ollama, Edge TTS. In progress.</sub>

## Other things

- [NoPE](https://github.com/AkseliHyv/junction2026-vendetta): a noise monitor on the Arduino UNO Q, made at Junction 2026. Each box guesses what's making the noise with an Edge Impulse model and uploads only summary numbers to a server that draws every box on a map.
- [Connect Suggests](https://github.com/ptchtrns/fonecta-since-ai): our entry for the Fonecta challenge at Since AI Hackathon 2026. It predicts businesses' holiday opening hours with gradient-boosted trees, asks owners over WhatsApp, Telegram or email whether the suggestion is right, and writes approved hours to Yext.
- [Preppi](https://github.com/Oplosity/preppi): a quiz platform for exam prep, made as a school project in a team of six. Next.js, Express and PostgreSQL.
- [Hunters of Artifacts](https://github.com/AkseliHyv/hunters-of-artifacts): a local multiplayer game in Python where players travel between airports collecting money, items and artifacts, with a [web version](https://github.com/AkseliHyv/hunters-of-artifacts-2) after it.
