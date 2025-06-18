# 🛠️ Case Study: PowerBI vs. RStudio - A Modern Comparison

This case study provides a detailed comparison of Microsoft Power BI and RStudio (Posit), two leading platforms for data analysis and visualization. It evaluates their capabilities, tech stacks, package ecosystems, and argues why RStudio excels for advanced analytics. A dedicated section guides R users on creating PowerBI-like visualizations and preparing for interviews at PowerBI-focused organizations. Modernized with vibrant banners and a sleek layout, this document serves as both a README and a comprehensive case study.

---

## 🧽 Overview of PowerBI and RStudio

### 🔹 PowerBI

Microsoft Power BI is a premier business intelligence platform designed for accessibility, enabling non-technical users to create interactive dashboards and reports.

### 🕘 RStudio

RStudio, an open-source IDE for the R programming language, is the tool of choice for data scientists and researchers.

---

## ⚖️ Capabilities Comparison

| Feature             | PowerBI                  | RStudio                                   |
| ------------------- | ------------------------ | ----------------------------------------- |
| Dashboard Creation  | Drag-and-drop tools      | Shiny apps with `plotly`, `flexdashboard` |
| Real-Time Updates   | DirectQuery              | `reactive()` and data polling             |
| Predictive Modeling | Azure ML, TensorFlow     | `tidymodels`, `caret`, `xgboost`          |
| Collaboration       | Power BI Service + Teams | `rmarkdown`, `bookdown`, `Posit Connect`  |

---

## 🌐 Use Case Diversity

PowerBI is great for enterprise-ready dashboards. RStudio is more diverse and technical, supporting fields like:

* Bioinformatics
* Econometrics
* Custom Machine Learning Solutions

---

## 🏗️ **Tech Stack Comparison**

### 💻 **🔹 PowerBI Tech Stack**

![Power Query](https://img.shields.io/badge/-Power%20Query-blue)
![DAX](https://img.shields.io/badge/-DAX-informational)
![Azure](https://img.shields.io/badge/-Azure-lightblue)
![SQL Server](https://img.shields.io/badge/-SQL%20Server-red)
![ASP.NET](https://img.shields.io/badge/-ASP.NET-purple)
![JavaScript](https://img.shields.io/badge/-JavaScript-yellow)
![HTML5](https://img.shields.io/badge/-HTML5-orange)

### 💻 **🕘 RStudio Tech Stack**

![R](https://img.shields.io/badge/-R-276DC3?logo=r)
![RMarkdown](https://img.shields.io/badge/-RMarkdown-darkgreen)
![Shiny](https://img.shields.io/badge/-Shiny-blueviolet)
![Rcpp](https://img.shields.io/badge/-Rcpp-grey)
![reticulate](https://img.shields.io/badge/-reticulate-lightgrey)
![SQL](https://img.shields.io/badge/-SQL-black)
![Spark](https://img.shields.io/badge/-Spark-orange)
![htmlwidgets](https://img.shields.io/badge/-htmlwidgets-cyan)

---

## 📦 **Installed Packages Comparison**

| 🔹 Category                | 🟡 PowerBI                | 🕘 RStudio Packages                                                                                                                                                                                                           |
| -------------------------- | ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📊 Data Visualization      | Built-in visuals          | ![ggplot2](https://img.shields.io/badge/-ggplot2-1f77b4) ![plotly](https://img.shields.io/badge/-plotly-d62728) ![lattice](https://img.shields.io/badge/-lattice-ff7f0e) ![ggvis](https://img.shields.io/badge/-ggvis-9467bd) |
| 🖼️ Interactive Dashboards | Dashboards, Slicers       | ![shiny](https://img.shields.io/badge/-shiny-17becf) ![flexdashboard](https://img.shields.io/badge/-flexdashboard-2ca02c) ![htmlwidgets](https://img.shields.io/badge/-htmlwidgets-cyan)                                      |
| 📈 Statistical Analysis    | DAX, R/Python Integration | ![stats](https://img.shields.io/badge/-stats-8c564b) ![tidymodels](https://img.shields.io/badge/-tidymodels-1f77b4) ![caret](https://img.shields.io/badge/-caret-7f7f7f) ![MASS](https://img.shields.io/badge/-MASS-bcbd22)   |
| 🤖 Machine Learning        | Azure ML, TensorFlow      | ![randomForest](https://img.shields.io/badge/-randomForest-ff9896) ![xgboost](https://img.shields.io/badge/-xgboost-98df8a) ![tidymodels](https://img.shields.io/badge/-tidymodels-1f77b4)                                    |
| 🪑 Data Preprocessing      | Power Query               | ![dplyr](https://img.shields.io/badge/-dplyr-17becf) ![tidyr](https://img.shields.io/badge/-tidyr-e377c2) ![data.table](https://img.shields.io/badge/-data.table-7f7f7f)                                                      |
| ⏱️ Time-Series Analysis    | Built-in Forecasting      | ![forecast](https://img.shields.io/badge/-forecast-1f77b4) ![tseries](https://img.shields.io/badge/-tseries-ff7f0e) ![xts](https://img.shields.io/badge/-xts-2ca02c)                                                          |
| 🌍 Geospatial Analysis     | ArcGIS, Power BI Maps     | ![sf](https://img.shields.io/badge/-sf-1f77b4) ![leaflet](https://img.shields.io/badge/-leaflet-2ca02c) ![tmap](https://img.shields.io/badge/-tmap-d62728)                                                                    |
| ❓ Missing Data Handling    | Power Query, R scripts    | ![mice](https://img.shields.io/badge/-mice-ff7f0e) ![Amelia](https://img.shields.io/badge/-Amelia-9467bd) ![missForest](https://img.shields.io/badge/-missForest-8c564b)                                                      |
| 📍 Report Generation       | Power BI Reports          | ![rmarkdown](https://img.shields.io/badge/-rmarkdown-darkgreen) ![knitr](https://img.shields.io/badge/-knitr-7f7f7f) ![bookdown](https://img.shields.io/badge/-bookdown-2ca02c)                                               |
| 📂 Database Connectivity   | SQL, ODBC, APIs           | ![DBI](https://img.shields.io/badge/-DBI-black) ![RMySQL](https://img.shields.io/badge/-RMySQL-blue) ![ROracle](https://img.shields.io/badge/-ROracle-red) ![odbc](https://img.shields.io/badge/-odbc-purple)                 |

---

Want this exported as a stylized GitHub-ready `README.md` with badges and markdown formatting? Just say the word!

Dashboard example project I built using the power of GrokAI, ChatGPT/OpenAI and RStudio!

# Advanced Aeristo AI Command Center Dashboard
# Run in RStudio, deploy to shinyapps.io or Docker
# Fixed 'risk_category' and 'predicted_defect' not found errors
# Enhanced with AI/ML, Power BI aesthetics, and enterprise features
# Added interactive map for leather supplier locations

# Load Libraries
library(shiny)
library(bs4Dash)
library(plotly)
library(dplyr)
library(lubridate)
library(DT)
library(xgboost)
library(randomForest)
library(isotree)
library(shinyWidgets)
library(shinycssloaders)
library(thematic)
library(DBI)
library(odbc)
library(writexl)
library(fontawesome)
library(shinyalert)
library(rsconnect)
library(leaflet) # Added for map visualization

# Enable thematic for consistent plotting
thematic_on()

# Custom Power BI-Inspired CSS
custom_css <- "
body {
  font-family: 'Roboto', sans-serif;
  background-color: #1A1A1A;
  color: #D3D3D3;
}
.main-header .navbar {
  background-color: #1A1A1A;
  border-bottom: 2px solid #8B5E3C;
}
.main-sidebar {
  background-color: #2B2B2B;
}
.box {
  background-color: #2B2B2B;
  border: 1px solid #8B5E3C;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}
.nav-tabs > li.active > a {
  background-color: #8B5E3C;
  color: #1A1A1A;
}
.btn-primary {
  background-color: #8B5E3C;
  border-color: #8B5E3C;
}
.btn-primary:hover {
  background-color: #A0522D;
  border-color: #A0522D;
}
.value-box {
  background-color: #2B2B2B;
  border: 1px solid #8B5E3C;
}
.footer {
  color: #D3D3D3;
  padding: 10px;
  font-size: 12px;
  position: fixed;
  bottom: 0;
  width: 100%;
}
.leaflet-container {
  background: #1A1A1A;
}
.leaflet-popup-content-wrapper {
  background-color: #2B2B2B;
  color: #D3D3D3;
}
.leaflet-popup-tip {
  background-color: #2B2B2B;
}
"

# UI ----------------------------------
ui <- bs4DashPage(
  dark = TRUE,
  header = bs4DashNavbar(
    title = "Aeristo AI Command Center",
    status = "dark",
    border = TRUE,
    fixed = TRUE
  ),
  sidebar = bs4DashSidebar(
    skin = "dark",
    status = "primary",
    elevation = 4,
    sidebarMenu(
      menuItem("QA Intelligence", tabName = "qa", icon = icon("microscope")),
      menuItem("Sustainability", tabName = "sustain", icon = icon("leaf")),
      menuItem("Supply Chain", tabName = "supply", icon = icon("truck"))
    )
  ),
  body = bs4DashBody(
    tags$head(tags$style(HTML(custom_css))),
    useShinyalert(),
    tabItems(
      tabItem(
        tabName = "qa",
        fluidRow(
          bs4ValueBoxOutput("defect_kpi", width = 3),
          bs4ValueBoxOutput("cost_kpi", width = 3),
          bs4ValueBoxOutput("anomaly_kpi", width = 3),
          downloadButton("qa_download", "Download QA Report", class = "btn-primary")
        ),
        fluidRow(
          box(
            title = "Defect Rate by Supplier (AI-Predicted)",
            width = 6,
            solidHeader = TRUE,
            withSpinner(plotlyOutput("qa_defect_plot"))
          ),
          box(
            title = "Predicted Cost of Defects",
            width = 6,
            solidHeader = TRUE,
            withSpinner(plotlyOutput("qa_cost_plot"))
          )
        ),
        fluidRow(
          box(
            title = "Supplier Locations and Batch Details",
            width = 12,
            solidHeader = TRUE,
            withSpinner(leafletOutput("supplier_map", height = "400px"))
          )
        )
      ),
      tabItem(
        tabName = "sustain",
        fluidRow(
          bs4ValueBoxOutput("co2_kpi", width = 3),
          bs4ValueBoxOutput("reach_kpi", width = 3),
          bs4ValueBoxOutput("iso_kpi", width = 3),
          downloadButton("sustain_download", "Download Sustainability Report", class = "btn-primary")
        ),
        fluidRow(
          box(
            title = "CO₂ Emissions per Treatment",
            width = 6,
            solidHeader = TRUE,
            withSpinner(plotlyOutput("co2_plot"))
          ),
          box(
            title = "Certification Status",
            width = 6,
            solidHeader = TRUE,
            withSpinner(DTOutput("cert_table"))
          )
        )
      ),
      tabItem(
        tabName = "supply",
        fluidRow(
          bs4ValueBoxOutput("ontime_kpi", width = 3),
          bs4ValueBoxOutput("stage_kpi", width = 3),
          downloadButton("supply_download", "Download Supply Chain Report", class = "btn-primary")
        ),
        fluidRow(
          box(
            title = "Current Order Timeline",
            width = 12,
            solidHeader = TRUE,
            withSpinner(plotlyOutput("order_timeline"))
          )
        )
      )
    ),
    tags$footer(
      HTML("Source: Aeristo ERP, Quality Control Systems, June 2025 | Powered by AI & R Shiny"),
      class = "footer"
    )
  )
)

# SERVER -----------------------------
server <- function(input, output, session) {
  
  # Initialize Data
  leather_batches <- reactive({
    set.seed(123)
    df <- data.frame(
      supplier = sample(c("Italy Prime", "Brazil Select", "India Luxe"), 50, replace = TRUE),
      batch_id = paste0("B", 101:150),
      defect_rate = runif(50, 0.01, 0.15),
      cost_per_sqft = runif(50, 18, 30),
      batch_date = as.Date("2025-01-01") + sample(1:180, 50, replace = TRUE),
      delivery_days = sample(3:10, 50, replace = TRUE)
    ) %>%
      mutate(
        risk_category = ifelse(defect_rate > 0.05, "High Risk", "Low Risk"),
        # Add fictional coordinates for suppliers
        lat = case_when(
          supplier == "Italy Prime" ~ 43.7696,
          supplier == "Brazil Select" ~ -23.5505,
          supplier == "India Luxe" ~ 19.0760
        ),
        lng = case_when(
          supplier == "Italy Prime" ~ 11.2558,
          supplier == "Brazil Select" ~ -46.6333,
          supplier == "India Luxe" ~ 72.8777
        )
      )
    
    if (!"risk_category" %in% colnames(df)) {
      stop("Error: 'risk_category' column not created in leather_batches_df")
    }
    message("leather_batches_df prepared with risk_category at ", Sys.time())
    df
  })
  
  compliance <- reactive({
    data.frame(
      treatment_type = c("Solvent-Based", "Water-Based", "Hybrid", "Natural Oil"),
      co2_kg_per_batch = c(120, 60, 80, 40),
      reach_certified = c(TRUE, TRUE, FALSE, TRUE),
      iso14001_certified = c(FALSE, TRUE, TRUE, TRUE)
    )
  })
  
  order_pipeline <- reactive({
    data.frame(
      order_id = paste0("ORD", 201:205),
      client = c("Gulfstream", "Bentley", "Embraer", "Dassault", "Yachtworks"),
      process_stage = c("Tanning", "QA", "Dyeing", "Cutting", "Shipping"),
      stage_start = as.Date(c("2025-06-01", "2025-06-03", "2025-06-04", "2025-06-05", "2025-06-06")),
      days_in_stage = c(4, 2, 3, 1, 5)
    )
  })
  
  # Initialize Alerts
  observe({
    shinyalert(
      title = "Welcome to Aeristo AI Command Center",
      text = "Explore AI-driven insights for QA, sustainability, and supply chain optimization.",
      type = "info",
      timer = 5000
    )
  })
  
  # Simulate SQL Connection
  conn <- reactive({
    tryCatch({
      message("Connected to simulated ERP at ", Sys.time())
      return(NULL)
    }, error = function(e) {
      shinyalert("Connection Error", e$message, type = "error")
      return(NULL)
    })
  })
  
  # AI/ML Models
  # Defect Prediction with XGBoost
  leather_batches_model <- reactive({
    df <- leather_batches()
    tryCatch({
      xgb_data <- as.matrix(df[, c("cost_per_sqft", "delivery_days")])
      xgb_model <- xgboost(
        data = xgb_data,
        label = df$defect_rate,
        nrounds = 10,
        objective = "reg:squarederror",
        verbose = 0
      )
      df$predicted_defect <- predict(xgb_model, xgb_data)
      message("XGBoost model trained successfully at ", Sys.time())
      df
    }, error = function(e) {
      message("XGBoost Error: ", e$message, " at ", Sys.time())
      shinyalert("XGBoost Error", "Failed to train defect prediction model. Showing actual defect rates only.", type = "warning")
      df$predicted_defect <- NA
      df
    })
  })
  
  # Supplier Risk Scoring with Random Forest
  leather_batches_rf <- reactive({
    df <- leather_batches_model()
    tryCatch({
      rf_data <- df[, c("cost_per_sqft", "delivery_days", "risk_category")]
      if (!"risk_category" %in% colnames(rf_data)) {
        stop("risk_category missing in rf_data")
      }
      rf_model <- randomForest(as.factor(risk_category) ~ cost_per_sqft + delivery_days, data = rf_data, ntree = 100)
      df$risk_score <- predict(rf_model, rf_data, type = "prob")[, "High Risk"]
      message("Random Forest model trained at ", Sys.time())
      df
    }, error = function(e) {
      shinyalert("Random Forest Error", e$message, type = "error")
      df$risk_score <- NA
      df
    })
  })
  
  # Anomaly Detection with Isolation Forest
  leather_batches_final <- reactive({
    df <- leather_batches_rf()
    tryCatch({
      iso <- isolation.forest(df[, c("defect_rate", "cost_per_sqft")], ntrees = 50)
      df$anomaly_score <- predict(iso, df[, c("defect_rate", "cost_per_sqft")])
      message("Isolation Forest model trained at ", Sys.time())
      df
    }, error = function(e) {
      shinyalert("Isolation Forest Error", e$message, type = "error")
      df$anomaly_score <- NA
      df
    })
  })
  
  # QA Intelligence Outputs
  output$defect_kpi <- renderbs4ValueBox({
    bs4ValueBox(
      value = sprintf("%.2f%%", mean(leather_batches_final()$defect_rate) * 100),
      subtitle = "Average Defect Rate",
      color = "primary",
      icon = icon("exclamation-triangle"),
      gradient = TRUE
    )
  })
  
  output$cost_kpi <- renderbs4ValueBox({
    cost_lost <- mean(leather_batches_final()$defect_rate * leather_batches_final()$cost_per_sqft * 100)
    bs4ValueBox(
      value = sprintf("$%.2f", cost_lost),
      subtitle = "Avg Cost Lost per Batch",
      color = "primary",
      icon = icon("dollar-sign"),
      gradient = TRUE
    )
  })
  
  output$anomaly_kpi <- renderbs4ValueBox({
    anomalies <- sum(leather_batches_final()$anomaly_score > 0.6, na.rm = TRUE)
    bs4ValueBox(
      value = anomalies,
      subtitle = "Anomalous Batches",
      color = ifelse(anomalies > 0, "danger", "primary"),
      icon = icon("bell"),
      gradient = TRUE
    )
  })
  
  output$qa_defect_plot <- renderPlotly({
    df <- leather_batches_final()
    p <- plot_ly(df, x = ~supplier, y = ~defect_rate, type = 'bar',
                 name = 'Actual Defect Rate', text = ~batch_id,
                 marker = list(color = 'rgba(139, 94, 60, 0.8)'))
    
    if ("predicted_defect" %in% colnames(df) && !all(is.na(df$predicted_defect))) {
      p <- p %>% add_trace(y = ~predicted_defect, type = 'scatter', mode = 'lines+markers',
                           name = 'AI-Predicted Defect', line = list(color = '#A0522D', dash = 'dash'))
    }
    
    p %>% layout(
      yaxis = list(title = 'Defect Rate (%)', range = c(0, max(df$defect_rate) * 1.2)),
      xaxis = list(title = 'Supplier'),
      paper_bgcolor = '#1A1A1A',
      plot_bgcolor = '#1A1A1A',
      font = list(color = '#D3D3D3'),
      showlegend = TRUE,
      hoverlabel = list(bgcolor = '#2B2B2B')
    )
  })
  
  output$qa_cost_plot <- renderPlotly({
    df <- leather_batches_final() %>%
      mutate(cost_lost = defect_rate * cost_per_sqft * 100)
    plot_ly(df, x = ~batch_id, y = ~cost_lost, type = 'bar', name = 'Cost of Defects',
            marker = list(color = 'rgba(133, 98, 66, 0.8)')) %>%
      layout(
        yaxis = list(title = 'Estimated Cost Lost ($)'),
        xaxis = list(title = 'Batch ID'),
        paper_bgcolor = '#1A1A1A',
        plot_bgcolor = '#1A1A1A',
        font = list(color = '#D3D3D3')
      )
  })
  
  output$qa_download <- downloadHandler(
    filename = function() { "Aeristo_QA_Report.xlsx" },
    content = function(file) {
      df <- leather_batches_final() %>%
        mutate(cost_lost = defect_rate * cost_per_sqft * 100) %>%
        select(batch_id, supplier, defect_rate, predicted_defect, cost_lost, risk_score, anomaly_score)
      write_xlsx(df, file)
    }
  )
  
  # Map Output for Supplier Locations
  output$supplier_map <- renderLeaflet({
    df <- leather_batches_final()
    leaflet(data = df) %>%
      addProviderTiles("CartoDB.DarkMatter") %>%
      addCircleMarkers(
        lng = ~lng,
        lat = ~lat,
        radius = 6,
        color = "#A0522D",
        fillColor = "#8B5E3C",
        fillOpacity = 0.8,
        popup = ~paste(
          "<b>Supplier:</b> ", supplier, "<br>",
          "<b>Batch ID:</b> ", batch_id, "<br>",
          "<b>Defect Rate:</b> ", sprintf("%.2f%%", defect_rate * 100), "<br>",
          "<b>Predicted Defect:</b> ", ifelse(is.na(predicted_defect), "N/A", sprintf("%.2f%%", predicted_defect * 100)), "<br>",
          "<b>Risk Score:</b> ", ifelse(is.na(risk_score), "N/A", sprintf("%.2f", risk_score)), "<br>",
          "<b>Anomaly Score:</b> ", ifelse(is.na(anomaly_score), "N/A", sprintf("%.2f", anomaly_score))
        )
      ) %>%
      setView(lng = 0, lat = 20, zoom = 2)
  })
  
  # Sustainability Outputs
  output$co2_kpi <- renderbs4ValueBox({
    bs4ValueBox(
      value = sprintf("%.0f kg", mean(compliance()$co2_kg_per_batch)),
      subtitle = "Avg CO₂ per Batch",
      color = "primary",
      icon = icon("cloud"),
      gradient = TRUE
    )
  })
  
  output$reach_kpi <- renderbs4ValueBox({
    reach_pct <- mean(compliance()$reach_certified) * 100
    bs4ValueBox(
      value = sprintf("%.0f%%", reach_pct),
      subtitle = "REACH Certified",
      color = ifelse(reach_pct < 100, "warning", "primary"),
      icon = icon("check-circle"),
      gradient = TRUE
    )
  })
  
  output$iso_kpi <- renderbs4ValueBox({
    iso_pct <- mean(compliance()$iso14001_certified) * 100
    bs4ValueBox(
      value = sprintf("%.0f%%", iso_pct),
      subtitle = "ISO 14001 Certified",
      color = ifelse(iso_pct < 100, "warning", "primary"),
      icon = icon("certificate"),
      gradient = TRUE
    )
  })
  
  output$co2_plot <- renderPlotly({
    plot_ly(compliance(), x = ~treatment_type, y = ~co2_kg_per_batch, type = 'bar',
            color = ~treatment_type, colors = c('#A0522D', '#8B4513', '#D2B48C', '#556B2F')) %>%
      layout(
        yaxis = list(title = 'CO₂ Emissions (kg)'),
        xaxis = list(title = 'Treatment Type'),
        paper_bgcolor = '#1A1A1A',
        plot_bgcolor = '#1A1A1A',
        font = list(color = '#D3D3D3'),
        showlegend = FALSE
      )
  })
  
  output$cert_table <- renderDT({
    datatable(
      compliance() %>%
        select(treatment_type, reach_certified, iso14001_certified),
      options = list(
        pageLength = 5,
        dom = 't',
        autoWidth = TRUE
      ),
      style = "bootstrap",
      class = "table-bordered table-striped",
      rownames = FALSE
    )
  })
  
  output$sustain_download <- downloadHandler(
    filename = function() { "Aeristo_Sustainability_Report.xlsx" },
    content = function(file) {
      write_xlsx(compliance(), file)
    }
  )
  
  # Supply Chain Outputs
  output$ontime_kpi <- renderbs4ValueBox({
    ontime_pct <- 100 * mean(order_pipeline()$days_in_stage <= 5)
    bs4ValueBox(
      value = sprintf("%.0f%%", ontime_pct),
      subtitle = "On-Time Stages",
      color = ifelse(ontime_pct < 80, "warning", "primary"),
      icon = icon("clock"),
      gradient = TRUE
    )
  })
  
  output$stage_kpi <- renderbs4ValueBox({
    avg_days <- mean(order_pipeline()$days_in_stage)
    bs4ValueBox(
      value = sprintf("%.1f Days", avg_days),
      subtitle = "Avg Stage Duration",
      color = ifelse(avg_days > 3, "warning", "primary"),
      icon = icon("hourglass-half"),
      gradient = TRUE
    )
  })
  
  output$order_timeline <- renderPlotly({
    df <- order_pipeline() %>%
      mutate(stage_end = stage_start + days_in_stage)
    plot_ly(df, x = ~stage_start, xend = ~stage_end, y = ~order_id, yend = ~order_id,
            type = 'scatter', mode = 'lines+markers',
            line = list(width = 12, color = '#8B5E3C'),
            marker = list(size = 8, color = '#A0522D'),
            text = ~paste("Client:", client, "<br>Stage:", process_stage),
            hoverinfo = 'text') %>%
      layout(
        title = 'Order Stage Durations',
        xaxis = list(title = 'Date', type = 'date'),
        yaxis = list(title = 'Order ID'),
        paper_bgcolor = '#1A1A1A',
        plot_bgcolor = '#1A1A1A',
        font = list(color = '#D3D3D3'),
        showlegend = FALSE
      )
  })
  
  output$supply_download <- downloadHandler(
    filename = function() { "Aeristo_Supply_Chain_Report.xlsx" },
    content = function(file) {
      df <- order_pipeline() %>%
        mutate(stage_end = stage_start + days_in_stage)
      write_xlsx(df, file)
    }
  )
  
  # Real-Time Anomaly Alerts
  observe({
    anomalies <- leather_batches_final()$anomaly_score > 0.6
    if (any(anomalies, na.rm = TRUE)) {
      shinyalert(
        title = "Anomaly Detected",
        text = paste("High anomaly score in batch(es):",
                     paste(leather_batches_final()$batch_id[anomalies], collapse = ", ")),
        type = "warning",
        timer = 0,
        closeOnClickOutside = TRUE
      )
    }
  })
}

# RUN -------------------------------
# To deploy to shinyapps.io:
# 1. Save this file as `app.R` in your project directory.
# 2. Set up your shinyapps.io account: rsconnect::setAccountInfo(name='your-account', token='YOUR_TOKEN', secret='YOUR_SECRET')
# 3. Deploy using: rsconnect::deployApp(appName = "AeristoAICommandCenter")
shinyApp(ui, server)



