# YVH Battle Droid Radar Module

This repository contains the source code for the YVH battle droid radar module, a part of the Seedtag codetest 2: Backend Engineer task.

## Requirements

- Node.js installed on your machine
- npm (Node Package Manager)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/leious32/yvh-battle-droid-radar.git

2. Navigate to the project directory:

   ```
   cd yvh-battle-droid-radar

3. Install dependencies using npm:

   ```
   npm install

4. To start the server, run the following command:

   ```
   node index.js

5. Clone this repository to your local machine:

   ```bash
   curl -X POST -H "Content-Type: application/json" -d '{"protocols":["avoid-mech"],"scan":[{"coordinates":{"x":0,"y":40},"enemies":{"type":"soldier","number":10}}]}' http://localhost:3000/radar

