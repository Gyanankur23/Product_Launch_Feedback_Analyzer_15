# Product_Launch_Feedback_Analyzer_15 CaseCraft Analytics Project Sprint Project 15

## 📣 Overview  
This project analyzes multi-platform product launch feedback using synthetic sentiment and engagement data. It blends VADER sentiment scoring, radar plots, and classification modeling to assess early launch success and guide strategy.

## 🎯 Objective  
To evaluate sentiment and engagement across Twitter, Instagram, YouTube, and Reviews, and predict launch success using early feedback signals.

## 🌐 Dataset & Features  
- Platforms: Twitter, Instagram, YouTube, Reviews  
- Entries: 1,000 synthetic feedback samples  
- Features:  
  - Text feedback  
  - Timestamp  
  - Sentiment score (VADER compound)  
  - Engagement volume  
- Derived: sentiment label (Positive, Neutral, Negative), engagement level (Low, Medium, High)

## 📊 Visual Explorations  
- **Radar Plot**: Average sentiment score by platform  
- **Streamgraph**: Engagement volume over time  
- **Violin Plot**: Sentiment score distribution  
- **WordClouds**: Platform-specific emotional vocabulary  
- **Confusion Matrix**: Engagement level prediction

## 🧠 Modeling & Insights  
- **Sentiment Analysis**:  
  - Twitter shows highest average sentiment  
  - Instagram leans neutral  
  - Reviews have widest sentiment spread  
- **Engagement Trends**:  
  - YouTube leads in volume  
  - Streamgraph reveals platform-specific spikes  
- **Classifier**:  
  - Model: Gradient Boosting  
  - Input: TF-IDF on feedback text  
  - Target: engagement level  
  - Accuracy: ~37% (weighted F1 ~0.32)

## 🔍 Key Takeaways  
1. **Platform Contrast**: Twitter excels in sentiment, YouTube in engagement  
2. **Visualization Utility**: Radar and streamgraphs offer intuitive comparisons  
3. **Model Performance**: Moderate accuracy in predicting engagement tiers  
4. **Strategic Leverage**: Early feedback signals can guide product iteration  
5. **Sentiment Spread**: Reviews show highest emotional variability

## ✅ Final Conclusion  
Multi-platform sentiment and engagement modeling offers a powerful lens into product launch dynamics. This framework supports early-stage strategy, platform targeting, and feedback-driven iteration—ideal for marketing and product teams seeking agile insights.