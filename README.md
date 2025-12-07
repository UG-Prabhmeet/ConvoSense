# ConvoSense

**ConvoSense** is a Python chatbot that interacts with users and performs sentiment analysis on conversations. It analyzes each user message and provides an overall mood trend for the entire conversation. The project also visualizes sentiment trends in a plot for easy understanding.  

## Features

- Real-time chatbot conversation  
- Statement-level sentiment analysis for each user message  
- Overall conversation sentiment detection  
- Mood trend visualization over the conversation  
- Sentiment mapped to emojis for better readability  
- Exportable sentiment trend plot  

## Technologies

- Python 3.x  
- Transformers (`DistilBERT` fine-tuned on SST-2)  
- Matplotlib  
- FPDF2  

## How to Run

1. Clone the repository:  
```bash
git clone <your-repo-link>
cd ConvoSense

## Install Required Libraries

```bash
pip install transformers torch emoji matplotlib fpdf2
