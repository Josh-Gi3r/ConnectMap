# 🌐 ConnectMap - Professional Network Analysis Tool

**View the demo here: https://josh-gi3r.github.io/ConnectMap/**

> **🔓 Recently Open Sourced** - Previously developed as private repositories as passion projects and technical experiments. Now releasing public demo versions of our core tools and concepts.

## 🚀 Overview

ConnectMap is a professional network analysis platform that maps and analyzes anyone's professional relationships, connections, and influence patterns. Originally built as a personal exploration into social network theory and relationship intelligence for business research.

### ✨ Key Features

- **Interactive Network Mapping** - Drag, zoom, and explore professional relationship networks
- **Multi-Degree Analysis** - Visualize 1st, 2nd, 3rd, and 4th degree connections
- **Relationship Intelligence** - Connection strength analysis and relationship types
- **Influence Scoring** - Algorithmic assessment of network influence and reach
- **Dynamic Filtering** - Filter by industry, connection strength, geographic location
- **Force-Directed Layouts** - Physically accurate relationship positioning with organic spread
- **Dark/Light Mode** - Professional themes for any research environment
- **Responsive Design** - Works seamlessly across all devices

## 🎯 Use Cases

### Professional Research Applications
- **Executive Recruitment**: Assess candidates' professional network reach and industry connections
- **Investment Due Diligence**: Analyze founders' and key personnel's relationship networks and influence
- **Business Development**: Map connection paths to target companies and decision makers
- **Competitive Intelligence**: Understand competitor networks and key relationships
- **Partnership Strategy**: Identify optimal introduction paths and mutual connections
- **Journalism & Investigation**: Research subject's professional relationships and influences
- **Sales Intelligence**: Map prospect networks and find warm introduction opportunities

## 🎬 Live Demo

**🌐 Try ConnectMap Live Demo: https://josh-gi3r.github.io/ConnectMap/**

Experience the full interactive network analysis platform with:
- **Connection Path Finding** - Discover how any two people are connected
- **Influence Sphere Analysis** - Visualize network reach and influence patterns  
- **Smart Search & Filtering** - Find people by name, company, or industry
- **Company Clustering** - Group relationships by organizational boundaries
- **Interactive Network Physics** - Drag people around and explore connections

⚠️ **This public version contains demo data only.** Full implementation concepts include:

- Live API connections to professional networks (LinkedIn, Crunchbase, etc.)
- Advanced relationship scoring and influence algorithms
- Real-time professional data integration and enrichment
- Enhanced privacy controls and data protection layers
- Comprehensive network analytics and business intelligence reporting

## 🛠️ Technology Stack

- **Frontend**: Vanilla JavaScript, D3.js v7, SVG/Canvas rendering
- **Visualization**: Force-directed graph algorithms, custom physics engine
- **Styling**: CSS3 with glassmorphism effects, responsive design
- **APIs**: *Hidden in production* - See `.env.example`

## 🏗️ Architecture

```
connectmap/
├── index.html              # Main application interface
├── styles/                 # CSS modules and themes
├── scripts/                # Core JavaScript modules
├── algorithms/             # 🔒 Proprietary network algorithms (hidden)
├── api-integrations/       # 🔒 Live data connectors (hidden)
├── assets/                 # Icons, images, demo data
├── .env.example           # Environment variables template
└── README.md              # This file
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/josh-gi3r/ConnectMap.git
   cd ConnectMap
   ```

2. **Open in browser**
   ```bash
   # Simple local server
   python -m http.server 8000
   # Or use Live Server extension in VS Code
   ```

3. **Explore the demo**
   - Drag companies around the network
   - Click bubbles for detailed company information
   - Use filters to explore by industry
   - Add random companies to see network evolution

## 🎯 Core Algorithms

### Network Positioning Engine
Our experimental force-directed algorithm optimizes person positioning based on:
- **Relationship Strength** - Close friends vs professional acquaintances
- **Industry Clustering** - People in similar fields naturally group together  
- **Mutual Connections** - Shared contacts influence positioning
- **Geographic Proximity** - Location-aware relationship mapping

### Connection Intelligence
Relationship scoring system analyzes:
- Direct professional connections (colleagues, clients)
- Social relationships (friends, mentors, alumni networks)
- Interaction frequency and communication patterns
- Mutual contacts and introduction paths
- Industry overlap and career progression patterns

*Full algorithm implementations represent experimental concepts and research directions.*

## 📊 Production Features

The complete concept includes additional experimental capabilities:

### 🔄 Real-time Data Sources
- LinkedIn API integration for professional profiles
- Social media relationship mapping  
- Contact list analysis and enrichment
- Professional directory connections
- Alumni network integration

### 📈 Advanced Analytics
- Relationship strength prediction models
- Network influence scoring
- Introduction path optimization
- Connection opportunity identification
- Professional network growth insights

### 🔐 Privacy & Security
- Granular privacy controls
- Secure data encryption
- User consent management
- Professional network etiquette
- GDPR compliance features

## 🎨 Customization

### Themes
```javascript
// Custom color schemes
const customTheme = {
  primaryColor: '#your-brand-color',
  industry: {
    tech: '#00d4ff',
    finance: '#64ffda',
    healthcare: '#ff6b6b'
  }
};
```

### Data Integration
```javascript
// Connect your data sources
const networkConfig = {
  dataSource: 'your-api-endpoint',
  updateInterval: 30000,  // 30 seconds
  algorithms: 'enhanced'  // Enterprise feature
};
```

## 📈 Performance Metrics

- **Rendering**: Handles 1000+ nodes at 60fps
- **Data Processing**: Real-time updates with <100ms latency  
- **Memory Usage**: Optimized for large datasets (10k+ companies)
- **Cross-browser**: Chrome, Firefox, Safari, Edge support

## 🤝 Collaboration & Development

This demo showcases core visualization concepts. Interested in collaborating or discussing implementation ideas?

### 📋 Potential Applications
- **Personal CRM**: Track and nurture professional relationships
- **Career Development**: Identify networking opportunities and mentors  
- **Team Building**: Visualize team connections and communication patterns
- **Recruitment**: Map candidate networks and referral paths

### 🎯 Technical Explorations
- Alternative social graph algorithms
- Privacy-preserving relationship analysis
- Mobile-first network visualization
- Real-time collaboration features

## 🔧 Development Setup

### Prerequisites
- Node.js 16+
- Modern browser with ES6 support
- Access to business intelligence APIs *(production only)*

### Environment Configuration
```bash
# Copy example environment file
cp .env.example .env

# Core Professional Network APIs
LINKEDIN_SALES_NAVIGATOR_API=your_linkedin_sales_api_key
CRUNCHBASE_ENTERPRISE_API=your_crunchbase_enterprise_key
CLEARBIT_PERSON_API=your_clearbit_person_enrichment_key

# Business Intelligence Sources
PITCHBOOK_API_TOKEN=your_pitchbook_data_access
APOLLO_IO_API=your_apollo_professional_database
ZOOMINFO_API_KEY=your_zoominfo_enterprise_key

# Social & Professional Graph APIs
GITHUB_TOKEN=your_github_api_token
TWITTER_API_V2_BEARER=your_twitter_enterprise_bearer

# Data Enrichment & Verification
FULL_CONTACT_API_KEY=your_fullcontact_api_key
PEOPLEDATALABS_API_KEY=your_people_data_labs_key

# News & Intelligence Sources
NEWS_API_KEY=your_news_api_key
GOOGLE_NEWS_API=your_google_news_key
```

## 📚 Documentation

- [API Reference](docs/api-reference.md) *(Implementation notes)*
- [Algorithm Details](docs/algorithms.md) *(Technical specifications)*
- [Integration Guide](docs/integration.md)
- [Performance Benchmarks](docs/benchmarks.md)

## 🤖 AI Integration

### Relationship Prediction
Our experimental models analyze:
- Communication patterns and frequency
- Professional career progression paths
- Mutual connection introduction likelihood
- Industry networking behavior patterns

### Smart Recommendations
- Introduction opportunity scoring
- Professional development path suggestions
- Networking event recommendations
- Career mentor identification

## 🔬 Research & Development

Current explorations:
- **Social Graph Analysis** - Algorithm development for relationship mapping
- **Privacy-First Networking** - Secure personal network visualization
- **Mobile Network Interfaces** - Touch-optimized relationship exploration
- **Real-time Collaboration** - Shared network building and insights

⚡ **Personal project by Josh Gier** ⚡

*Experimental network visualization concepts for business relationship mapping.*
