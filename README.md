# Earnings Call AI Analysis
This project analyzes AI-related discussions in earnings call transcripts of major tech companies using natural language processing and sentiment analysis.

## Project Structure
- `transcripts/`: Contains earnings call transcript files
- `case_study.ipynb`: Main analysis notebook
- `ai_terms.csv`: List of AI-related terms for analysis
- `mag7_transcripts.csv`: Mapping file with transcript metadata
- `requirements.txt`: Python dependencies

## Setup
1. Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your Anthropic API key:
     ```
     ANTHROPIC_API_KEY=your_api_key_here
     ```

## Usage
Open `case_study.ipynb` in Jupyter Notebook or VS Code to run the analysis.

## Analysis Components
- Term frequency analysis
- Sentiment analysis using Claude API
- Topic modeling using BERTopic
- Time series analysis of AI mentions
- Company-specific AI strategy analysis
=======
# earnings_call_analysis
>>>>>>> 5815404bb24efe99f35f9b60e106a932cf1c70cb
