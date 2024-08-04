## Docker Compose Instructions

1. **Build and Pull the front-end and all micro services Images**

   ```sh
   docker-compose -f docker-compose.yml build

2. **Run all micro-services container inclusive front-end**

   ```sh
   docker-compose -f docker-compose.yml up -d 

3. **Stop all micro-services container inclusive front-end**

   ```sh
   docker-compose -f docker-compose.yml down