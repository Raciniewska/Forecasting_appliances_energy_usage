# Forecasting_appliances_energy_usage

Analysis of forcasting algoriths for appliances energy usage prediction in R.

Folder Data - folder z plikami danych wykorzystywanymi do realizacji obliczeń
	-energydata_complete.csv oryginalny i pełny zbiór danych
	-energy_data_after_analysis.csv zbiór danych po etapie analizy
	-energy_data_after_processing.csv zbiór danych po etapie przetwarzania danych
	-energy_data_train.csv zbiór treningowy
	-energy_data_test.csv zbiór testowy
Folder R - kod źródłowy 
	-dataAnalyser_notepad.Rmd kod źródłowy dla etapu analizy
	-dataProcessor_notepad.Rmd kod źródłowy dla etapu przetwarzania danych
	-linearRegression_notepad.Rmd kod źródłowy dla modelu regresji liniowej
	-ridgeRegression_notepad.Rmd kod źródłowy dla modelu regresji liniowej z regularyzacją L2
	-lassoRegression_notepad.Rmd kod źródłowy dla modelu regresji liniowej z regularyzacją L1
	-SVR_notepad.Rmd kod źródłowy dla modelu SVR
	-RandomForestRegression_notepad.Rmd kod źródłowy dla modelu regresji lasu losowego
	-lights_for_appliances_pred.Rmd kod źródłowy dla modelu regresji lasu losowego z wykorzystanie przewidywanego atrybutu 		“lights”
