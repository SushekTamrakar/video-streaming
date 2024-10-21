# video-streaming

# Adaptive Bitrate Video Player

This project is a Next.js application featuring an adaptive bitrate video player built with shadcn/ui components. It supports HLS (HTTP Live Streaming) and allows users to change video quality on the fly.

## Features

- Adaptive bitrate streaming using HLS
- Play/Pause functionality
- Seek bar for navigation
- Volume control with mute toggle
- Quality selection for different bitrates
- Responsive design
- Dark mode support

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or later)
- npm (v6 or later)

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/nextjs-video-player.git](https://github.com/SushekTamrakar/video-streaming.git
   cd nextjs-video-player
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Run the development server:
   ```
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

The video player is set up to play a sample HLS stream. To use your own video:

1. Open `app/page.tsx`
2. Locate the `VideoPlayer` component
3. Change the `src` prop to your HLS stream URL:
   ```jsx
   <VideoPlayer src="https://your-hls-stream-url.m3u8" />
   ```

## Customization

### Changing Styles

This project uses Tailwind CSS for styling. You can customize the appearance by modifying the Tailwind classes in the components or by updating the `tailwind.config.ts` file.

### Adding New Features

To add new features to the video player:

1. Open `components/VideoPlayer.tsx`
2. Modify the component to include your new feature
3. If needed, add new UI components from shadcn/ui or create custom components

## Deployment

This project is set up for easy deployment on Netlify. To deploy your own instance:

1. Fork this repository to your GitHub account
2. Sign up for a Netlify account if you haven't already
3. In Netlify, click "New site from Git"
4. Choose your forked repository
5. Set the build command to `npm run build`
6. Set the publish directory to `out`
7. Click "Deploy site"

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
