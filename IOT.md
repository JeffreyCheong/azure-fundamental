# IOT DATA Flow

- Collect
  - Collect time series data coming from different sources, formats & rates
- Process
  - Parse, Normalize, Enrich, Transform
  - Notify (Operator/System)
- Store
  - Store in multi-layered time series data store optimized for a variety of analysis
- Analyze
  - Explore and Monitor
  - Perform operational analysis
  - Models for learning and predictions

  Run ad-hoc queries for monitoring operationalized using asset-based analysis;
  Use model for machine learning inference and make predictions


# Time Series Model 
- Semantic Model
- Contextualization
- Easy to use
- Computations

Event Data -> Time series instance definition/ instance fields
           -> Hierachy definition              -> Type Definition

Varibles
- Kind (used to specify the type of signal being analyzed)
- Value (used to specify the value column in telemetry)
- Filter (used to specify matching condition while computing)
- Interpolation(used to reconstruct the missing points in telemetry)
- Aggregate(used to specify reduction operation type to be performed on the telemetry)

Continous telemetry(numeric - pressure in 1 minute or 30 sec) or discrete telemetry(categorial - wall on/off)

- Time Series Query
  - Query data at scale
  - Reconstruct or reduce the data
  - Access via explorer or APIs
  - String based on expression language

  
