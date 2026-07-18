# School Fee Extraction - Cloud Agent Instructions

## School-Specific Level Mappings

When extracting pre-KG level fees, use these specific level names:

### Neev Academy
- Pre-KG Level Name: **Pre-K1** (not "Pre-KG" or "Early Years")
- Annual Fee: ~4,65,000 INR
- Duration: Annual (can be split as Per Term: 2,32,500 INR)

### Bangalore International School (BIS)
- Pre-KG Level Name: **Early Years**
- Annual Fee: ~3,90,225 INR (Total of all components)

### Indus International School Bangalore (IISB)
- Pre-KG Level Name: **Reception**
- Annual Fee: ~4,23,000 INR

### Stonehill International School
- Pre-KG Level Name: **Nursery** (P1-P3)
- Fee: ~$10,740 USD (Annual)
- Note: Fees in USD

## Extraction Rules

1. Always match the exact level name used by the school
2. Extract annual tuition/education fees where available
3. Duration is typically "Annual" or "Per term"
4. Mark confidence as "High" if fees found clearly, "Medium" if from context
5. Note currency (INR vs USD) in comments

## Special Cases

- **Neev Academy**: Has multiple program levels (Early Start, Toddler1, Pre-K1, K1/K2). Extract Pre-K1 specifically.
- **TISB (The International School of Bangalore)**: Access via SharePoint link if available
