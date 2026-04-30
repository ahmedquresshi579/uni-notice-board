# uni-notice-board
devops project
# University Digital Notice Board

A static website for COMSATS University Islamabad, Lahore Campus displaying academic notices, exam schedules, and admission information.

## Tech Stack
- HTML5, CSS3
- Parcel (bundler)
- HTMLHint (HTML linting)
- Stylelint (CSS linting)
- Docker (containerization)
- GitHub Actions (CI/CD)

## CI Pipeline
1. HTMLHint - validates HTML
2. Stylelint - validates CSS
3. Parcel Build - bundles the website
4. Docker Build & Push - containerizes and publishes

## Docker Hub
Image available at: `docker pull YOUR_DOCKERHUB_USERNAME/uni-notice-board:latest`

## Local Development
```bash
npm install
npm run lint:html
npm run lint:css
npm run build
```