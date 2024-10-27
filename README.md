
# DevTube

DevTube is a self-hosted video-sharing platform that functions as a personalized "YouTube for yourself." This application includes Google OAuth integration, video management, and channel creation features, among other functionalities.

## Getting Started

### Prerequisites

- Node.js installed on your machine.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/DevTube.git
   cd DevTube
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the project:
   ```bash
   npm run dev
   ```

   This command will launch the project locally on your machine.

## Features

### Auth and Integrations
- Google OAuth for login/logout functionality.
- MongoDB integration using Mongoose for data storage.
- Bunny Stream for video handling.
- Real-time updates with Socket.io.
- Image upload and management via ImageKit.
- Multer for file handling and upload.

### Channel Management
- Create, update, and manage channels.
- Unique handle suggestion if a chosen handle already exists.
- Retrieve channel details by handle, ID, or UID.
- Subscribe/Unsubscribe functionality.
- Channel notification settings.

### Video Management
- Upload, update, and categorize videos.
- Real-time upload status updates.
- Webhook-based video status updates (isShort, length, category, aspect).

### Tags and Hashtags
- Retrieve videos/shorts based on tags and hashtags.

### Comments
- Add, like/dislike, reply, and delete comments.
- Retrieve comments for each video.

### Studio Features
- View all videos/shorts of a channel.
- Edit videos.
- Track video views and watch time.

### Utility Functions
- `getTimestamp`: Get timestamp from date.
- `generateID`: Create unique IDs for channels and videos.
- `formatNumber`: Display large numbers in a readable format (K, M).
- `generateSignature`: Generate BunnyCDN signatures.
- `createUniqueHandle`: Create unique handles for channels.

## Technologies / Libraries

### Frontend
- EJS
- CSS
- JavaScript
- Socket.io
- Tus JS Client

### Backend
- Express.js
- Mongoose
- Bunny (for video services)
- Passport and Passport Google OAuth for authentication

## Issues & Contributions

Currently, deployment is in progress, and help with deployment or feature enhancement is welcome. For any questions, please open an issue or submit a pull request.
