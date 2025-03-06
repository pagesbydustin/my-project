# A/V Documentation

Detailed instructions for A/V setup and live-streaming.

For equipment specifications, see our [Equipment List](equipment.md).

## Audio

The Allen & Heath Qu-16 is a digital mixer that allows you to manage and control audio for live events. Here’s a brief overview of how audio works on this mixer:

1. **Signal Flow**: Audio signals from microphones and instruments are connected to the input channels on the mixer. Each channel processes the audio signal independently.
2. **Preamp and Gain**: The preamp boosts the audio signal to a usable level. Adjust the gain to ensure the signal is strong without clipping.
3. **EQ (Equalization)**: Use the EQ controls to adjust the frequency response of each channel. This helps to enhance the sound quality by boosting or cutting specific frequencies.
4. **Dynamics**: Apply compression and gating to control the dynamic range of the audio signal. Compression reduces the volume of loud sounds, while gating eliminates unwanted noise.
5. **Mixing**: Use the faders to balance the levels of all input channels. The main mix fader controls the overall output level sent to the speakers.
6. **Effects**: Add reverb, delay, and other effects to enhance the audio. Effects can be applied to individual channels or the entire mix.
7. **Monitoring**: Use the headphone output and monitor mix controls to listen to the audio. This allows you to make adjustments in real-time.
8. **Output**: The final mixed audio is sent to the main outputs, which are connected to the PA system or recording devices.

For detailed setup instructions, refer to the [Setup Instructions](../index.md#setup-instructions).

For detailed software configuration, see our [OBS Studio Documentation](software.md#obs-studio).

For church contact information, see our [Contact Page](../extras/contact.md).

### Feedback

Feedback occurs when the sound from the speakers is picked up by the microphones and re-amplified, creating a loop that results in a high-pitched squeal. To prevent feedback:

- **Microphone Placement**: Position microphones away from speakers and monitors.
- **Gain Structure**: Set the gain levels properly to avoid excessive amplification.
- **EQ Adjustments**: Use the EQ to cut frequencies that are prone to feedback.
- **Directional Microphones**: Use directional microphones that pick up sound from a specific direction, reducing the chance of feedback.

### Microphones

Different types of microphones are used for various purposes:

- **Dynamic Microphones**: Durable and versatile, ideal for live sound applications. They handle high sound pressure levels and are less sensitive to feedback.
- **Condenser Microphones**: More sensitive and provide a wider frequency response, making them suitable for studio recordings and capturing detailed sound. They require phantom power.
- **Lavalier Microphones**: Small, clip-on microphones used for hands-free operation, often in presentations and theater.
- **Shotgun Microphones**: Highly directional microphones used to capture sound from a distance, commonly used in film and video production.

## Video

### Camera Setup

- **PTZ Optics**: Position the PTZ Optics camera at the designated spot and connect it to the network.
- **Tailair Cameras**: Position the two Tailair cameras at their designated spots and connect them to the network.

### OBS Studio Configuration

- Open OBS Studio on the computer.
- Add video sources from the PTZ Optics and Tailair cameras.
- Configure the video settings (resolution, frame rate, etc.).

## Live Streaming

### Streaming Setup

- Open OBS Studio on the computer.
- Add audio sources from the audio mixer.
- Configure the streaming settings (resolution, bitrate, etc.).
- Start the live stream to the desired platform (YouTube, Facebook, etc.).

### Troubleshooting

#### No Video Signal

- Check the network connections between the cameras and the computer.
- Ensure the cameras are powered on and recognized by the computer.

#### No Audio Signal

- Verify the microphone connections to the audio mixer.
- Check the audio mixer settings and ensure it is recognized by the computer.

#### Streaming Issues

- Check the internet connection.
- Verify the streaming settings in OBS Studio.
