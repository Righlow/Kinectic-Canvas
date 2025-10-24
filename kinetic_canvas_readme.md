# Kinetic Canvas

## Concept Overview

Kinetic Canvas is a web app that transforms fitness data into immersive, generative 3D worlds. Instead of traditional charts and graphs, it rewards users visually with every workout by evolving their personal world. A social feature allows you to add friends and explore the stages or "worlds" they have unlocked, creating a shared universe of motion.

## Unique Features

- **Generative Fitness Worlds**: Workout data controls terrain, color, and light in a 3D environment
- **Social Universe**: Add friends and see their current stages or worlds. Explore their environments in a read-only mode
- **Rewards-Based Progress**: New environments unlock only when workouts are completed
- **Creative Visualization**: Reimagines fitness tracking as data-driven art rather than statistics
- **Immersive Exploration**: Interactive 3D camera controls

## Inspiration

Kinetic Canvas combines the data-driven precision of Strava with the emotional storytelling of generative art:

- **Strava and Fitbit Dashboards**: Track performance through graphs and stats
- **Nike Run Club**: Gamifies running through badges and challenges
- **Data Art by Refik Anadol**: Transforming data into visual motion
- **Three.js Generative Art Projects**: Interactive 3D visualizations

## How It Uses Data

The app connects to the **Strava API** to fetch live workout metrics. This data feeds into the 3D rendering system, driving parameters such as:

- **Distance**: Affects terrain size or height
- **Heart Rate**: Influences color palette intensity
- **Speed**: Controls particle velocity
- **Calories**: Determines lighting intensity
- **Streak Consistency**: Unlocks new layers or biomes, triggers growth of plants

Each metric translates into visual elements, creating a dynamic representation of your fitness journey.

## User Experience

Kinetic Canvas replaces traditional fitness dashboards with a living world that evolves as the user moves. Instead of just seeing numbers, users see growth, color, and light.

- Friends' progress appears as orbiting "worlds", creating a motivational interconnected environment
- This turns personal data into a shared emotional and creative experience, blending art, fitness, and community

## Target Audience

- Fitness enthusiasts who find conventional data displays uninspiring
- People interested in self-expression through data
- Competitive individuals interested in gaming elements
- Users motivated by visual progress
- Those seeking artistic rewards for consistent activity

## Tech Stack

### Front-end
- HTML, CSS, JavaScript
- Three.js / Babylon.js (3D rendering)

### Back-end
- Node.js
- Express

### Database
- MongoDB

### API Integration
- Strava API



