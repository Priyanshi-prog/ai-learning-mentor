# ai-learning-mentor
Autonomous AI mentor that tracks coding performance, detects weaknesses, and adapts daily learning plans.

**Problem Statement:**
Learning to code effectively—especially for competitive programming and technical interviews—is difficult due to the lack of personalized guidance. Most learners practice problems randomly across platforms like LeetCode, GeeksforGeeks, and CodeChef without understanding their actual weaknesses, learning patterns, or progress over time.

Existing platforms provide problems and basic statistics but fail to:
- Identify topic-wise weaknesses accurately
- Analyze solving behavior (time, hesitation, repeated mistakes)
- Adapt daily learning plans dynamically
- Intervene when learners stagnate or deviate from goals
- 
As a result, learners waste time, lose motivation, and plateau.

**Proposed Solution:**
AI Learning Mentor is an autonomous learning coach that continuously observes a learner’s coding activity, analyzes performance and behavior, and dynamically plans a personalized daily learning roadmap. The system functions as a self-adapting mentor, not just a recommendation engine.

**Autonomous Learning Loop**
The mentor operates using a closed-loop autonomous system:
1. **Observe** – Collects coding performance data (problem difficulty, time taken, success rate).
2. **Analyze** – Detects weak topics, slow-solving patterns, and stagnation signals.
3. **Plan** – Generates a personalized daily practice plan.
4. **Intervene** – Adjusts the plan when the learner struggles, improves, or goes off-track.
5. **Learn** – Maintains long-term memory to track improvement and skill decay.

**Tech Stack:**
- Python
- SQLite (local storage)
- Rule-based logic + lightweight ML
- Streamlit / CLI (for visualization)

**Architecture Diagram:**
![Architecture Diagram](architecture.png)

- Data ingestion captures coding activity
- Analysis engine detects weak areas and slow patterns
- Memory module tracks long-term learning trends
- Planning engine generates daily personalized roadmap
- Intervention module adapts plans autonomously
