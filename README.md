# Movie Transcript Scraper

![Thumbnail](https://github.com/kirubel-web/ScriptMiner/blob/main/Movie_Transcript_Scrap.png?raw=true)
![website](https://github.com/kirubel-web/ScriptMiner/blob/main/website.png?raw=true)

This Python script is designed to scrape movie transcripts from [subslikescript.com](https://subslikescript.com). It extracts links to movie scripts from the main page and saves individual scripts to text files.

## Dependencies

- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
- [Requests](https://docs.python-requests.org/en/latest/)

Install dependencies using:

```bash
pip install beautifulsoup4 requests
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/kirubel-web/ScriptMiner.git
cd ScriptMiner
```

2. Run the script:

```bash
python scraper.py
```

The script will fetch movie transcript links from the main page and save individual transcripts to text files.

## File Structure

- `scraper.py`: The main Python script for scraping movie transcripts.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Documentation for the project.

## Output

The scraped movie transcripts are saved in individual text files. The file name corresponds to the movie title.

## Contributing

If you would like to contribute to this project or report issues, please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
