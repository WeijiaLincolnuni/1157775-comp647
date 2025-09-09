# 1157775
## dataset
AI Tool Usage by Indian College Students 2025
Dataset address: https://www.kaggle.com/datasets/rakeshkapilavai/ai-tool-usage-by-indian-college-students-2025/data

## potentially explore with the dataset
The main analysis is whether the use of AI tools affects academic performance.

1. The impact of various factors on academic performance

The correlation heatmap shows a slight negative correlation between Trust_in_AI_Tools and Impact_on_Grades (-0.047), while Daily_Usage_Hours is positively correlated with academic performance (0.057).
The bar plot also confirms this.

2. Does the number of hours used daily using AI tools affect learning outcomes?

The scatterplot shows a slight positive correlation.
The boxplot and KDE plot show that 1–3 hours of daily AI use has a stable neutral to positive impact on academic performance.
However, students with excessive use (>4 hours) show a mixed performance, with some showing significant improvements and others declining. This suggests that the impact of AI tools is not linear; rather, it is effective in moderation, while excessive use can be detrimental.

3. Is there an inverse relationship between trust and learning outcomes? Is there an inverse relationship between trust and academic performance?

The correlation heatmap shows a slight negative correlation (-0.047) between Trust_in_AI_Tools and Impact_on_Grades.
The boxplot is unclear, suggesting that the impact on grades is indeed minimal.

4. Is grade level correlated with average time spent using AI tools?

Correlation bar plot analysis shows that there is little correlation between Year_of_Study and Daily_Usage_Hours.
The lineplot shows that students in different grades have different average AI usage hours, indicating that AI tool use has become widespread across all grades. Based on the line plot, countplot, Preferred_AI_Tool, and AI_Tools_Used data, ChatGPT, Gemini, and Copilot are the most popular tools. ChatGPT has the largest user base, and students using Copilot may see more positive performance gains in technical tasks. Niche tools (Claude and Bard) have fewer users.

5. Which AI tools do students prefer across different grades, and how do usage patterns change?

The line plot shows similar distributions across grade levels, with usage concentrated between 1 and 3 hours.
However, tool preferences may vary: for example, older students may more frequently use Copilot/ChatGPT for programming and research, while younger students may prefer Bard for homework and writing.

6. What factors influence usage hours?

Do_Professors_Allow_Use: The countplot shows whether professors allow it. It has no significant impact on whether students use AI tools. However, when professors allowed the use of AI tools, the usage rates of ChatGPT and the ChatGPT/Gemini/Copilot combination were slightly higher than when professors prohibited the use of AI tools. When professors prohibited the use of tools, the usage rates of other tools and combinations were slightly higher.

7. Differences in Students' Usage Habits for Different AI Tools

The KDE analysis shows that ChatGPT, Gemini, and Copilot have more distinct user groups and peaks, while Claude/Bard has fewer and more dispersed usage.
This analysis also reflects the typical usage durations of different tools (for example, ChatGPT has peaks between 1 and 4 hours, Copilot has peaks between 1 and 2 hours, and Gemini has peaks between 3 and 4 hours).

## Summary:
Through EDA, we found that:
1. AI tool Daily_Usage_Hours and Trust_in_AI_Tools are important factors influencing grades. Professor attitude has a relatively minor impact on AI usage.
2. Moderate use of AI tools combined with critical trust is more conducive to learning.
3. Students choose different AI tools based on their goals and needs. 
4. The effectiveness of different AI tools in learning scenarios deserves further exploration.