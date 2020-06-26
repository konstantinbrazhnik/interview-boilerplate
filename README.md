# Juris Interview Boilerplate

This repository contains a boilerplate for a Juris interview and document generation. It's all you need! Literally!

## Run It

Want to test it out? Run it by visiting: 

https://builder.getjuris.com/run?i=https://raw.githubusercontent.com/JurisProject/interview-boilerplate/master/interview.json&o=https://raw.githubusercontent.com/JurisProject/interview-boilerplate/master/output.md

Here's a breakdown of the URL:

`https://builder.getjuris.com/run` is the URL that runs the interview  
`i=` is a URL link to the raw JSON of the interview file  
`o=` is a URL link to the raw MD of the output file you want to generate a PDF from

### Cloning this Repo

If you clone this repo to start, then you will need to modify the above link as follows:

Change the `i=` link to `https://raw.githubusercontent.com/[YOUR GITHUB USERNAME]/[YOUR NEW REPO NAME]/master/interview.json`

Change the `o=` link to `https://raw.githubusercontent.com/[YOUR GITHUB USERNAME]/[YOUR NEW REPO NAME]/master/output.md`

## Edit It

If you want to edit this interview, the easiest way to do it is via our builder and the GitHub editor.

### Editing the Template

Editing the template is a piece of cake. Just click on the edit button in GitHub and write your template in Markdown format. We currently just support headers and paragraph tags, so don't get too fancy. We'll have support for tables and other formatting in the future.

### Editing the Interview

If you want to edit the interview, head on over to the creator part of our builder and use the embedded SurveyJS builder to create alter your interview. Once you're happy with it, go to the `JSON Editor` tab, copy all of the JSON code and over-write your entire `interview.json` file here in GitHub.

You can access the SurveyJS builder for this interview at the following link:

https://builder.getjuris.com/creator/creator?i=https://raw.githubusercontent.com/JurisProject/interview-boilerplate/master/interview.json&o=https://raw.githubusercontent.com/JurisProject/interview-boilerplate/master/output.md

## Embed It

Ready to deploy? With Juris Builder, you don't need any server infrastructure to deploy this to your clients or as an internal tool, simply embed the final interview in an iFrame by using the following code:

`<iframe src="https://builder.getjuris.com/run?i=https://raw.githubusercontent.com/JurisProject/interview-boilerplate/master/interview.json&o=https://raw.githubusercontent.com/JurisProject/interview-boilerplate/master/output.md&hideUI=1" />`

That's it! It's literally that easy.
