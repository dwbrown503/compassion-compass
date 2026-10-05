# Compassion Compass

Compassion Compass is a community-centered platform designed to connect people, organizations, ministries, and volunteers around meaningful opportunities to serve, support, and strengthen their communities.

The goal is simple: make it easier to find needs, offer help, coordinate resources, and create lasting positive impact.

## Vision

Communities become stronger when compassion is organized into action.

Compassion Compass helps individuals and organizations:

- Discover local needs
- Coordinate outreach efforts
- Track service opportunities
- Support vulnerable populations
- Build stronger community connections
- Measure impact over time

---

## Core Features

### Community Support

- Find local service opportunities
- Identify community needs
- Connect volunteers with organizations
- Coordinate assistance efforts

### Resource Network

- Share resources and information
- Recommend trusted community services
- Map available support options
- Improve access to assistance programs

### Volunteer Engagement

- Volunteer sign-up and coordination
- Opportunity management
- Community outreach tracking
- Service history and participation records

### Organization Tools

- Create and manage initiatives
- Publish needs and requests
- Coordinate volunteers
- Monitor engagement and outcomes

### Impact Tracking

- Service activity tracking
- Community engagement metrics
- Program participation reporting
- Outcome measurement

---

## Technology Stack

- React
- TypeScript
- Supabase
- PostgreSQL
- Authentication
- Cloud Storage
- Real-time Data Synchronization

---

## Project Structure

```text
src/
├── components/
├── pages/
├── services/
├── hooks/
├── utils/
├── types/
└── assets/
```

---

## Getting Started

### Prerequisites

- Node.js (LTS)
- npm
- Supabase Account

### Installation

```bash
git clone https://github.com/dwbrown503/compassion-compass.git

cd compassion-compass

npm install
```

### Environment Variables

Create a `.env.local` file:

```env
SUPABASE_URL=YOUR_SUPABASE_URL
SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
```

### Start Development Server

```bash
npm run dev
```

---

## Database

Recommended tables:

```text
profiles
organizations
volunteers
opportunities
resource_requests
community_needs
service_records
messages
```

All user data should be protected using Row Level Security (RLS).

---

## Security

Compassion Compass is designed with privacy and security in mind.

- Secure authentication
- Role-based permissions
- Encrypted connections
- Protected community data
- Row Level Security policies

---

## Roadmap

### Phase 1

- Authentication
- User profiles
- Organization profiles
- Opportunity listings

### Phase 2

- Volunteer management
- Resource directory
- Request matching

### Phase 3

- Messaging
- Notifications
- Mobile experience

### Phase 4

- Analytics
- Community impact reporting
- AI-assisted recommendations

### Phase 5

- Regional partnerships
- Multi-organization collaboration
- Advanced reporting

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Submit a pull request

---

## Mission

Compassion Compass exists to help communities transform care, concern, and compassion into meaningful action by connecting people with opportunities to serve and support one another.

---

## License

This project is licensed under the MIT License.
