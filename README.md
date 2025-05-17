# Impact of Network Conditions on Audio Streaming Service Reliability

# Overview:

- This research project explores how different network conditions (delay, jitter, and packet loss) affect the Quality of Experience (QoE) of three major music streaming platforms: Apple Music, Spotify, and SoundCloud.
- I evaluated how each service's unique streaming protocols and audio compression techniques perform under varying network conditions.

## Key Features and Findings:

- Comparative Analysis: I compared the performance of Apple Music, Spotify, and SoundCloud under simulated network conditions.
- Network Conditions: My research focused on the impact of delay (latency), jitter (variation in packet arrival time), and loss (packet loss) on streaming quality.

- Streaming Technologies: The project examines the streaming protocols and audio codecs used by each service:

- Apple Music: AAC, ALAC [cite: uploaded:SYE-Poster-Image.jpg-8c55d4da-4deb-42df-bb56-593a3a26a7b9].

- Spotify: Spotify Streaming Protocol (SPS) [cite: uploaded:SYE-Poster-Image.jpg-8c55d4da-4deb-42df-bb56-593a26a7b9].

- SoundCloud: HTTP Live Streaming (HLS) [cite: uploaded:SYE-Poster-Image.jpg-8c55d4da-4deb-42df-bb56-593a26a7b9].

- Hardware and Setup: The project utilizes a Raspberry Pi, adapters, and an Ethernet connection to the SLU network to simulate different network conditions [cite: uploaded:SYE-Poster-Image.jpg, [cite: uploaded:SYE-Soko (1).pdf].

## Results:

- Spotify maintains the best balance between audio quality and streaming stability [cite: uploaded:SYE-Poster-Image.jpg].

- Apple Music offers superior sound quality under optimal conditions but is significantly susceptible to network disruptions [cite: uploaded:SYE-Poster-Image.jpg].

- SoundCloud effectively manages fluctuating network conditions but at the expense of consistent audio quality [cite: uploaded:SYE-Poster-Image.jpg].

## Future Research: 

- I plan to further explore the specific adaptive technologies used by these platforms to gain deeper insights into their operational efficiencies and potential areas for improvement.

## Technical Details:

- The project involved setting up a Raspberry Pi to simulate network conditions.

- Collected scores for different configurations.

