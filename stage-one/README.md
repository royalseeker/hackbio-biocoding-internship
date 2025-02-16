
# HackBio Internship: Stage 1

## Threonine Team - Bioinformatics & Computational Biology
[Team Members](#team-members)

### Overview
This repository contains solutions for the **HackBio Internship Stage 1** activities completed by the **Threonine Team**. The activities focus on fundamental bioinformatics and computational biology concepts, including DNA translation, logistic growth simulation, and Hamming distance calculations.

---

## Table of Contents
1. [Translating DNA](#translating-dna)
2. [Simulating Logistic Growth](#simulating-logistic-growth)
   - Generating 100 growth curves
   - Plotting growth curves
3. [Time to Reach 80% of Maximum Growth](#Time-to-Reach-80%-of-Maximum-Growth)
4. [Hamming Distance](#hamming-distance)
   
---

## Translating DNA
### `translating(sequence)`
This function converts a given **DNA sequence** into a corresponding **protein sequence** using a predefined codon-to-amino acid mapping.

#### **How it works:**
- The function takes a DNA sequence as input.
- It reads the sequence in **triplets (codons)**.
- It maps each codon to its corresponding **amino acid** using a dictionary.
- The translated protein sequence is returned as a list of amino acids.

#### **Example Usage:**
```python
sequence = "ATGGCTGATGCAATT"
translating(sequence)
```

---

## Simulating Logistic Growth
### `logistic_growth(L, k, ...)`
This function simulates **logistic population growth**, commonly used in microbial growth models.

#### **Key Phases:**
1. **Lag Phase:** Initial slow growth.
2. **Exponential Phase:** Rapid population growth.
3. **Stationary Phase:** Growth stabilizes as resources deplete.
4. **Death Phase:** Population declines.

#### **How it works:**
- The function takes parameters such as **carrying capacity (L)** and **growth rate (k)**.
- It assigns random durations to each growth phase.
- It computes population sizes over time.
- Returns a time-series dataset.

#### **Generating 100 Growth Curves:**
```python
df_curves = generate_100_growth_curves(L=1000, k=0.4)
print(df_curves.head())
```

#### **Plotting the Growth Curves:**
```python
plt.figure(figsize=(10, 6))
for i in range(1, 101):
    subset = df_curves[df_curves["replicate"] == i]
    plt.plot(subset["time"], subset["population"], alpha=0.3)
plt.xlabel("Time")
plt.ylabel("Population")
plt.title("100 Simulated Logistic Growth Curves")
plt.grid(True)
plt.show()
```

## Time to Reach 80% of Maximum Growth:
```python
times_80 = time_to_80_percent_growth(df_curves)
```
This function determines the **time at which each replicate reaches 80% of its maximum population size**.

---

## Hamming Distance
### `hamming_distance(slack_username, twitter_handle)`
This function computes the **Hamming distance** between two strings.

#### **How it works:**
- Compares two strings character-by-character.
- If the strings have different lengths, it **pads** the shorter one with spaces.
- Counts the number of **differences**.

#### **Example Usage:**
```python
slack_username, twitter_handle = "slack", "slack_username"
hamming_distance(slack_username, twitter_handle)
```

---

## Team Members
- [@royalseeker](https://github.com/royalseeker)
- [@mahertantouch](https://github.com/mahertantouch)
- [@iamaparnapadmanabhan](https://github.com/iamaparnapadmanabhan)

---


