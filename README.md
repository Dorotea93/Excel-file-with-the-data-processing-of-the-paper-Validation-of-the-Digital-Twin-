# Excel-file-with-the-data-processing-of-the-paper-Validation-of-the-Digital-Twin-
Excel file containing the data processing of the paper Validation of the Digital Twin applied to a 2.79 kW self-consumption installation
In the Datasheet tab you can see the datasheet information of the PV panel, i.e. the data of the electrical characteristics of the panel.
In the DATA_WHATERLINK tab you can see all the data downloaded from the weather station and used for the calculations (wind speed, ambient temperature and solar irradiance).
In the Real_inst_dataPV_5min tab you can find all the data downloaded from the real PV installation which are the current and voltage input to the inverter, in order to calculate the PV power at the inverter input which is the product of the voltage and the current.
In the Equations_temp_panel tab you can see the equations of the different formulas to calculate the panel temperature.
In the Calculations_DT__min_average_1, Calculations_DT__min_average_2 and Calculations_DT__min_average_3 tabs, one can see the calculations performed for data processing to calculate the error metrics MSE, RMSE and MAE using the PV cell temperature estimation equations from Correa-Betanzo et al., 2018, Ayaz et al., 2014 and Skoplaki et al., 2008 respectively. And for each of those models to estimate the PV cell temperature equation are combined with the equation to calculate PV power from Jain et al., 2020 (Eq. 1) and Hong & Pula, 2023 (Eq. 2). With these data, Tables 2 and 3 of the article have been created.
In the tab Calculations_DT__min_media_2_ca you can see the tables and the way in which the parameters of Tables 4, 5 and 6 of the article have been calculated and obtained.
In the DT_PV_Energy tab you can see how the data in table 7 have been calculated.
In the Calculations_DT_avar_high tab the results of average and high solar radiation are compared in the same table.
