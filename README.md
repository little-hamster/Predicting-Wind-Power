# Predicting-Wind-Power
In 2024, 91.9 percent of the world used electricity but about 80% of used energy sources will run out and cause an irreversible increase in carbon dioxide which warms the climate and damages ecosystems [1,2,3,4]. Wind power generates about 11 percent of the world’s demand for electricity [5]. In this paper we are interested in answering how can temperature, relative humidity, dew points, wind speeds, wind direction, wind gusts in meters per second at 100 meters above the surface help predict the power created by wind turbines? We used machine learning and regression. The random forest regressor had a Mean Squared Error (MSE) of 0.013 and a coefficient of determination (R2) of 0.741. The linear regression had a MSE of 0.035 and R2 0f -0.130. The decision tree regressor had a MSE of 0.025 and an R2 0f 0.630. The random forest regressor is the most useful of the three models we tried in predicting wind power generated based on various factors. It still isn’t super accurate. In this paper, we demonstrated that we can create a strong predictor for wind power generation for different wind turbines. With the Random Forest model that outperformed the others, we can estimate ideal wind turbine locations to build and generate the most optimal power outputs for an area. This creates a great environmental friendly alternative that communities can benefit from.
---
# References
[1] World Bank, 2024, “Access to Electricity (% of Population),” World Development Indicators, https://data.worldbank.org/indicator/EG.ELC.ACCS.ZS.

[2] Environmental and Energy Study Institute, 2021, "Fossil Fuels," Environmental and Energy Study Institute, https://www.eesi.org/topics/fossil-fuels/description.

[3] Council on Foreign Relations, 2023, "Sources of Energy: A Comparison," CFR Education, https://www.cfr.org/education/learn/reading/sources-energy-comparison.

[4] United Nations, [n.d.], "What Is Climate Change?," United Nations, https://www.un.org/en/climatechange/what-is-climate-change [accessed Oct. 5, 2026].

[5] World Wind Energy Association, 2026, "WWEA Annual Report 2025: Global Wind Power in 2025: Record Growth and Emerging Challenges," World Wind Energy Association, Bonn, Germany, https://wwindea.org/GlobalStatistics [Accessed Oct. 6, 2026].
