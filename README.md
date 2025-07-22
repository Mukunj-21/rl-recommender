# ShopGenie 🛒

**ShopGenie** is a reinforcement learning–powered research platform that simulates user behavior in an e-commerce environment. It enables you to experiment with and evaluate different recommender system algorithms using virtual user personas and a dynamic product catalog—all through an interactive Streamlit dashboard.

---

## 🌟 Features

- **Diverse Product Catalog:**  
  - 250+ products spanning 10 categories (Home, Beauty, Sports, Books, Clothing, Electronics, Toys, etc.)
  - Rich item attributes: price, quality, brand (15 brands), color, popularity, and release date.
- **Realistic User Simulation:**  
  - Six distinct, pre-defined user personas—each with unique shopping motivations (e.g., price-sensitive, brand-focused, novelty-seeking, etc.).
- **Multiple Recommendation Strategies:**  
  - Random, Popularity-based, and PPO reinforcement learning agents.
- **Fully Interactive Dashboard:**  
  - Use Streamlit to select user types, run simulations, visualize recommended products, and track key metrics like CTR and BTR in real time.
- **Research & Experimentation Ready:**  
  - Designed for custom experiments, reproducible research, and detailed evaluation with metrics visualization and W&B logging.

---

## 🧑‍💻 How ShopGenie Works

1. **Setup:** Choose simulated user types and recommenders directly from the dashboard.
2. **Simulation:** The system presents product recommendations, and user agents respond based on their preferences (click, buy, or skip products).
3. **Feedback & Learning:** RL agents update policies based on user feedback (rewarded by clicks/buys).
4. **Analysis:** Track metrics such as click-through rate (CTR) and buy-through rate (BTR) live.
5. **Experimentation:** Use W&B integration for logging, hyperparameter sweeps, and analyzing different agent behaviors.

---

## 🚀 Getting Started

1. **Clone This Repository**
    ```
    git clone https://github.com/Mukunj-21/shopgenie.git
    cd shopgenie
    ```

2. **Install Dependencies**  
    Python 3.12+ recommended.
    ```
    pip install -r requirements.txt
    ```

3. **Launch the Streamlit Dashboard**
    ```
    streamlit run app.py
    ```

4. **Explore and Experiment!**  
    Play with user types, recommender strategies, and see instant feedback and analytics.

---

## 🛠 Tech Stack

- **Programming:** Python 3.12+
- **RL Environment:** Gymnasium
- **RL Algorithms:** PPO (via Stable-Baselines3)
- **Web Interface:** Streamlit
- **Neural Networks:** PyTorch
- **Data Handling:** Pandas, NumPy
- **Experiment Tracking:** Weights & Biases (W&B)
- **Synthetic Data:** Faker

---

## 📊 Example Use Cases

- Compare the efficiency of classic and RL-based recommendation strategies.
- Visualize how different user personas influence recommendation performance.
- Benchmark new RL algorithms in a simulated e-commerce setup.
- Generate synthetic user/recommender data for research or testing.

---

## 📈 Roadmap

- Add more diverse user personas (e.g., trend-followers, seasonal buyers)
- Integrate additional RL and Bandit algorithms
- Support for cold-start scenario simulation
- Option to plug in real-world e-commerce datasets
- Built-in A/B testing module for different recommenders

---

## 🤝 Contributing

Contributions, feedback, and ideas for new user models or algorithms are welcome! Please open an issue or a PR.

---

## License

MIT License

---

**ShopGenie** — Experiment. Learn. Innovate.  
A safe and interactive playground to advance your recommender system research—no real user data required!