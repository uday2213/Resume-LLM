


## 🛠 How It Works
ResuLLMe now supports both OpenAI and Gemini, empowering the application to enhance résumés with even more powerful and diverse language models, providing users with smarter, more accurate career guidance.  

ResuLLMe receives your previous CV as a PDF or Word Document. Then, it uses LLMs to:
* Improve the résumé following published résumé guidelines by well-reputed schools
* Convert the résumés to a JSON Resume format
* Render the JSON resume using LaTeX to generate a new PDF of the enhanced resume

> [!IMPORTANT]  
> ResuLLMe was updated to support macOS and Windows. For that to happen, we had to switch the LaTeX engine. If you prefer the old rendering behavior, check the code in the `v1` branch.

> [!NOTE]  
> If ResuLLMe fails to extract data from your CV, you can manually download the JSON output, edit it and re-render at the "Render JSON Resume" tab

## 🏃 Running Natively


To run the app locally, you will need to install [Pixi](https://prefix.dev/):

```
curl -fsSL https://pixi.sh/install.sh | bash
```

Lastly, to run ResuLLMe locally, execute:

```
pixi run run-app
```



### 🪄 Running with Docker

To run ResuLLMe locally, the simplest way is to use Docker:

```
docker-compose up -d
```

This will make the app avaialable at [`https://localhost:8501/`](https://localhost:8501/)


## 🤲 Contributing

ResuLLMe is an open source project.

If you want to contribute, open a [Pull requests](https://github.com/360macky/project-name/pulls). 
All contributions are welcome, but some that would particularly be useful to the community are:
* Fixes in existing LaTeX templates
* Adding new LaTeX templates
* Improved prompts
* Support for other LLMs (e.g. Bard, Claude, LLaMA)
# Resume-LLM
