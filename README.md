# chatgptvisual - Accenture-Super-Consultant

In order to run this project, make sure you have the environment set up. Please note that this project is currently operable on Windows.

You will need:

1. OpenAI API Key from https://www.openai.com/api/
2. PowerBi from https://powerbi.microsoft.com/en-us/downloads/
3. NodeJS from https://nodejs.org/en/download
4. Install pbiviz using 'npm i -g powerbi-visuals-tools@latest' from the command prompt after downloading NodeJS
5. Install axios using 'npm install axios' from the command prompt after downloading NodeJS
6. Run 'npm i' to install any remaining dependencies you may need

After ensuring the environment is set up, you will need to change your OpenAI API Key in src/visual.ts and updating the apiKey field.

Once this is complete, run 'pbiviz package' in the command prompt. This will generate a .pbiviz file in the dist folder.

In the 'Visualizations' pane select "Import from file" and import this.pbiviz file.
