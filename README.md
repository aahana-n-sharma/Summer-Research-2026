# Summer-Research-2026
Network LLMS and Analysis in Cybersecurity
Gemini CLI installed globally with npm:
npm install -g @google/gemini-cli
- ran into issues with file permissions, npm approve-scripts wasn't working
- instead edited the config:
  npm config set allow-scripts=@github/keytar,node-pty --location=user
  npm install -g @google/gemini-cli
  
