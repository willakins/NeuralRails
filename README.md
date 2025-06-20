# NeuralRails

NeuralRails is a personal playground for exploring the integration of AI tools into a Ruby on Rails application. This project serves as a learning lab for building intelligent, full-stack features using modern AI techniques alongside the Rails framework.

## 🚀 Goals

- Learn and practice modern Ruby on Rails development
- Integrate AI tools such as:
  - Large language models (OpenAI, Hugging Face)
  - Image generation or processing models
  - Recommendation systems
- Experiment with AI-assisted features in a web app
- Understand how to build and deploy smart applications end-to-end

## 🧠 AI Tools to Explore

- **OpenAI GPT models** – natural language interfaces, summarization, chat
- **Whisper** – speech-to-text transcription
- **Stable Diffusion / DALL·E** – image generation from text
- **Sentence Transformers** – semantic search and vector similarity
- **LangChain / LLM orchestration** – structured workflows

## 🛠️ Tech Stack

- **Backend**: Ruby on Rails 7
- **Frontend**: Hotwire / Turbo (default), may experiment with React
- **Database**: PostgreSQL
- **AI APIs**: OpenAI, Hugging Face, others via REST/GraphQL
- **Deployment**: TBD (e.g., Render, Fly.io, Heroku)

## 📦 Setup

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/NeuralRails.git
cd NeuralRails

# Install dependencies
bundle install
yarn install # if using js/css bundling

# Setup database
rails db:setup

# Start the Rails server
rails server
