Business Context
Megaline is a telecom provider looking to retire legacy mobile plans. To support this, the company wants to recommend newer plans, Smart or Ultra-based on subscriber behavior. By automating this process, Megaline can improve customer satisfaction and align users with better-suited plans.

Dataset Description
Each row represents monthly behavior for a single subscriber. Features include:

calls: Number of calls made
minutes: Total call duration (in minutes)
messages: Number of text messages sent
mb_used: Mobile internet usage (MB)
is_ultra: Target variable, where 1 = Ultra plan, 0 = Smart plan
Goal
Develop a machine learning classification model that accurately predicts whether a subscriber should use the Smart or Ultra plan.
Success Criteria: Final model must achieve ≥75% accuracy on the test dataset.
