# Elevator Floor Paradox
### 📌 Author's remark
I initially planned to explore probability, but I also have some interesting experiments in mind that I might want to conduct in the future. As a result, I decided to keep both READMEs.
Also, the plan here is not finalized yet, and there are so many things to revise. Thank you. 

## 📌 Project Overview
This project is inspired by the **Birthday Paradox**.  
Instead of asking *"What’s the probability that two people share the same birthday?"*,  
we ask:  

👉 *"What’s the probability that two or more people in an elevator share the same floor?"*

The idea came from everyday experience: when entering an elevator, it often feels like multiple people choose the same floor. This similarity to the Birthday Paradox motivated me to experiment and simulate probabilities for different elevator sizes.

---

## 🎯 Goals
- Model the probability of at least two people selecting the same floor.
- Run experiments for different elevator capacities (e.g., up to 14 people).
- Compare results across different numbers of floors (e.g., a 10-floor building vs. a 50-floor building).
- Visualize how the probability changes as more people enter.

---

## 🔧 How It Works
1. **Simulation-based approach**  
   - Randomly assign floors to people in the elevator.  
   - Check if any two (or more) share the same floor.  
   - Repeat for many trials to estimate probability.

2. **Analytical approach (optional)**  
   - Use combinatorics similar to the Birthday Paradox formula.  
   - Calculate exact probabilities for small numbers.

---

## 📊 Example Questions
- With 14 people in an elevator and 20 floors, what is the probability at least 2 share the same floor?  
- How quickly does the probability rise as we increase the number of people?  
- Does it become "almost certain" (close to 100%) before reaching max capacity?

---

## 🚀 Features (Planned)
- [ ] Run Monte Carlo simulations.  
- [ ] Support variable number of floors and people.  
- [ ] Plot graphs to visualize probability curves.  
- [ ] Compare simulation results with analytical formulas.  

---

## 🛠️ Tech Stack
- Python (simulation & plotting)
- Libraries: `numpy`, `matplotlib`

---

## 📌 Inspiration
- [The Birthday Paradox](https://en.wikipedia.org/wiki/Birthday_problem)  
- Elevator thought experiments & everyday curiosity

---

## 📈 Future Extensions
- Allow user to input custom building sizes (e.g., 30 floors, 100 floors).  
- Compare multiple buildings or elevator systems.  
- Extend beyond elevators (e.g., parking lots, meeting rooms).  
