# 🌱 AI for Weed Science Workshop
### Exploring Weed Seed Persistence with Conversational AI

**Workshop Goal:**  
In this session, you’ll use AI tools to explore a real dataset from a published study on weed seedbank persistence. You’ll see how conversational AI can help summarize, visualize, and interpret agronomic data — and also where it falls short.

---

## 🧩 Background
Weed seeds differ in how long they persist in the soil. This dataset, from Davis *et al.* (2016), measures physical, chemical, and physiological seed traits for 11 arable weed species, helping explain why some seeds remain viable for years while others do not.

You’ll use AI tools to explore:
- Which traits are most associated with seedbank persistence  
- Which weed species are “high risk” for long-term persistence  
- What new questions or management insights AI might suggest  

---

## 👥 Step 1: Form Groups
- Break into groups of **2–3 students**.  
- Each group will use a **different AI tool** (so we can compare results later).  
  Example options:
  - ChatGPT (with data upload or “Code Interpreter” enabled)  
  - Google NotebookLM  
  - Gemini Advanced  
  - Claude.ai (Anthropic)  
  - Copilot / Perplexity.ai  

---

## 🌐 Step 2: Download the Dataset
You’ll retrieve the dataset directly from the USDA Ag Data Commons — just like a researcher would.  

1. Go to:  
   👉 [https://agdatacommons.nal.usda.gov/articles/dataset/Data_from_Interspecific_variation_in_persistence_of_buried_weed_seeds_follows_trade-offs_among_physiological_chemical_and_physical_seed_defenses/24660489](https://agdatacommons.nal.usda.gov/articles/dataset/Data_from_Interspecific_variation_in_persistence_of_buried_weed_seeds_follows_trade-offs_among_physiological_chemical_and_physical_seed_defenses/24660489)

2. Under **“Files”**, download:
   - `Davis et al 2016_Seed Persistence_0.xlsx` You may view the file in google sheets here: https://docs.google.com/spreadsheets/d/1kYJzzBHqHLG_XTk8wO74ASjUarlkrOcE/edit?usp=sharing&ouid=100373362533979950619&rtpof=true&sd=true
   - `DataDictionary.csv` https://github.com/marklocklear/NEWSS/blob/main/DataDictionary.csv

3. Save them somewhere easy to find (e.g., Desktop or Downloads).

---

## 🤖 Step 3: Upload to Your AI Tool
Each student group uploads both files into their chosen AI tool.  

**Important:**  
Include *both* the dataset and the data dictionary so the AI understands what each variable means.  

If your tool allows, add this **setup prompt**:  
> “This dataset is from Davis et al. (2016), examining weed seed persistence across 11 arable species. The Excel file includes seed traits (physical, chemical, and physiological) and persistence measures. The CSV is the data dictionary describing each column. Use these together to understand the relationships among variables.”

---

## 💬 Step 4: Core Prompts
Each group should copy/paste and run these prompts in sequence.

Add/upload the two data files (the csv and excel files) to your AI tool and begin with the prompts below.

### 🧠 Prompt 1 – Understand the dataset
> I am attaching data from https://agdatacommons.nal.usda.gov/articles/dataset/Data_from_Interspecific_variation_in_persistence_of_buried_weed_seeds_follows_trade-offs_among_physiological_chemical_and_physical_seed_defenses/24660489. Can you Summarize the dataset for me? What are the main variables, and what do they measure biologically? Which variable represents “seed persistence,” and what are the possible explanatory traits? 

*(Goal: get the AI to describe the structure and meaning of the data. But also ensure the AI has the correct understanding of the data and its purpose)*

---

### 📈 Prompt 2 – Explore relationships
> Based on this dataset, which seed traits appear most strongly correlated with seed persistence?  
> Explain these relationships in biological terms.

*(Goal: identify key drivers like seed coat thickness, phenolic content, or respiration rate.)*

---

### 🌾 Prompt 3 – Management application
> If we wanted to prioritise which weed species to target for seed-bank depletion strategies, which ones are high risk for long-term persistence, and why?

*(Goal: interpret the data for weed management decisions.)*

---

### 💡 Prompt 4 – Reflection and creativity
> What are other interesting or unexpected questions I could ask about this dataset?  
> Suggest two or three ideas and answer one of them.

*(Goal: encourage curiosity and question generation.)*

---

## 🔍 Step 5: Group Reflection
Within your group, discuss:
1. Did your AI tool interpret the dataset correctly?  
2. Were any answers clearly wrong, misleading, or oversimplified?  
3. How confident would you be using these AI-generated insights to inform actual management decisions?  
4. How did your tool’s performance compare to another group’s?  

*(Tip: note differences in reasoning, clarity, and correctness — not just accuracy of numbers.)*

---

## 🗣️ Step 6: Whole-Group Share-Out
Each group briefly shares:
- Which AI tool you used  
- One **useful insight** you gained  
- One **thing the AI got wrong or confused**
- Where the answers consistant, similar or different across AIs
- How you might use (or not use) AI tools like this in your future research  

---

## 🧭 Instructor Notes
- Time: ~45 minutes total  
  - 5 min intro  
  - 10 min data download/setup  
  - 15–20 min AI exploration  
  - 10 min debrief/discussion  
- Emphasize that this is **not about getting the “right answer”**, but about understanding how AI *interprets and reasons* with real agronomic data.  
- Optionally, use a shared Jamboard or Google Doc for group notes comparing AI outputs.

---

## 🧰 Optional Extension
If you have extra time or want a deeper dive:
> Ask the AI to visualize the relationship between seed coat thickness and persistence.  
> What trend do you see? Does it align with published weed ecology theories?

---

### 📎 Links
- [Dataset on USDA Ag Data Commons](https://agdatacommons.nal.usda.gov/articles/dataset/Data_from_Interspecific_variation_in_persistence_of_buried_weed_seeds_follows_trade-offs_among_physiological_chemical_and_physical_seed_defenses/24660489)  
- [Davis AS et al., *Functional Ecology*, 2016](https://doi.org/10.1111/1365-2435.12661)
