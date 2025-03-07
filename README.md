# Home of Projects

Home of Projects is a Telegram mini-app designed for developers to showcase their projects. Users can upload their projects, which are then posted to a dedicated Telegram channel for community feedback, exposure, and collaboration opportunities.

## Features

- **Project Upload**: Easily upload your projects through a user-friendly interface.
- **Community Feedback**: Gain insights and feedback from a vibrant tech community.
- **Exposure**: Share your work with a wider audience and connect with like-minded innovators.
- **Collaboration**: Find potential collaborators for your projects.

## Deployment

- **Backend**: Deployed on [Render](https://render.com), using FastAPI to handle requests and interact with the Telegram API.
- **Frontend**: Deployed on [Vercel](https://vercel.com), providing a responsive interface for users to submit their projects.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- Python and pip for the backend.
- A Telegram bot token and channel ID.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kenawak/home-of-projects.git
   cd home-of-projects
   ```

   If you have already cloned the repository without submodules, you can initialize and update them with:
   ```bash
   git submodule update --init --recursive
   ```

2. **Backend Setup**:
   - Navigate to the `backend` directory.
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Set up environment variables in a `.env` file:
     ```
     TOKEN=your_telegram_bot_token
     WEBHOOK_URL=your_webhook_url
     ```

3. **Frontend Setup**:
   - Navigate to the `frontend` directory.
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

### Usage

- Access the frontend at `http://localhost:3000` to upload projects.
- The backend will handle the data and post it to the specified Telegram channel.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the open-source community for their invaluable contributions.
- Special thanks to [Harish](https://harishgarg.com) for the inspiration to create a FastAPI quickstart for Render.
