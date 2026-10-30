# Part C: Specialised Technology

## C1 Fundamental Concepts
The chosen specialized technology is **Agentic AI combined with Multimodal Computer Vision**. Agentic AI operates autonomously by evaluating goals, planning sequential actions, using external tools (such as price lookups), and making decisions with minimal user intervention. Combined with Multimodal Vision Transformers, the system can parse images and text simultaneously.

### Architecture Flow
1. **Input Perception:** Seller uploads unstructured product photos.
2. **Multimodal Processing:** Vision models analyze item type, brand, color, and visual defects (scratches/dents).
3. **Agentic Reasoning Loop:** The agent queries market price indexes, calculates fair value, generates ad details, and handles buyer messages autonomously.

## C2 Frameworks, Models, and Tools
1. **LangChain / LangGraph:** Framework for orchestrating stateful multi-agent workflows and tool invocation.
2. **YOLOv8 / Vision Transformers (Qwen-VL / CLIP):** Multimodal object detection and visual feature extraction models for defect analysis and tag generation.
3. **Scikit-learn (Gradient Boosting):** Machine learning models used to process historical marketplace data for dynamic price recommendations.

## C3 Fit to Problem, Benefits, and Alternatives
* **Fit to Problem:** Directly eliminates seller upload friction and buyer response latency on Mudah.my.
* **Benefits:** Speeds up ad creation from ~5 minutes to under 30 seconds and improves listing data consistency.
* **Limitations & Risks:** Potential image misclassification or hallucinations; compute cost and processing latency.
* **Alternative Comparison:** Static rule-based form wizards. Static wizards are cheaper but require 10+ manual entry steps and do not solve communication delays. Agentic AI is selected to maximize automation.
