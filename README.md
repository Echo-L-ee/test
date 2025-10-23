import os
import time
import argparse
import pandas as pd
from Bio import Entrez
from dotenv import load_dotenv
from pathlib import Path

# --- Setup ---
load_dotenv()  # loads .env if present
Entrez.email = os.getenv("EMAIL", "apriloctober17@hotmail.com")
Entrez.api_key = os.getenv("NCBI_API_KEY","48035e8fafb81cfbe03a235c56c14ecc3909")
<img width="1406" height="576" alt="image" src="https://github.com/user-attachments/assets/d10ad18a-7812-47ce-bfca-4bb38a16ad90" />
