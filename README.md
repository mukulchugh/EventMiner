# EventMiner

EventMiner is an open source tool built on Next.js that scrapes Google search result pages to discover events based on specified keywords. It extracts event data and metadata into structured formats like JSON or CSV.

## Features

- **Keyword-Based Scraping:** Search for events using targeted keywords
- **Metadata Extraction:** Capture event details including dates, locations, and descriptions
- **Structured Output:** Export data in JSON and CSV formats
- **Built on Next.js:** Modern web-based experience with excellent performance
- **Open Source:** Customize the scraping logic to fit your needs

## Getting Started

### Prerequisites

- Node.js (v14+)
- npm or Yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/eventminer.git
cd eventminer

# Install dependencies
npm install
# or
yarn install
```

### Usage

Start the development server:

```bash
npm run dev
```

Access the web interface at `http://localhost:3000`

For CLI usage:

```bash
node scraper.js --keyword "music festival" --pages 5
```

## Configuration

Edit `config.js` to customize:

- Search keywords
- Number of pages to scrape
- Output format and location

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

[MIT License](LICENSE)
