This set of files are associated with my JMeter performance tests.  These tests hit various WebstaurantStore URLs for 15 mins at a rate of less than 5 RPM.  

My Test Plan is set up in the following way:
  * RunTime Controller to run the test for 900s
  * Random Controller to randomize REQs between multiple URLs
  * Constant Throughput Timer to target 4.8 RPM (under 5 RPM)
  * Summary Report to provide many base metrics
  * HTTP Response Time Graph

Artifacts provided:
  * run1
    * Webstaurant_TestResults_15min_5RPM_Summary_run1_053024 Excel 
        * Raw data from run1
        * Per URL Latency Graph (created in Excel)
        * Summary Report with all test result metrics, notations, and explanations
    * Webstaurant_15min_5RPM_Summary_Report_run1_053024.jpg
  * run2
    * Webstaurant_TestResults_15min_5RPM_Summary_run2_053024 Excel
        * Raw data from run2
        * Summary Report with all test result metrics, notations, and explanations
    * Webstaurant_15min_5RPM_Summary_Report_run2_053024.jpg
    * Webstaurant_15min_5RPM_JMeter_Graph_run2_053024.jpg
  * Test Plan
    * WebstaurantStore Perf Test wGraph 053024.jmx
