# My .NET Core API

This project is a simple .NET Core API that provides weather forecast data.

## Project Structure

- **Controllers**: Contains the API controllers.
  - `WeatherForecastController.cs`: Handles HTTP requests related to weather forecasts.
  
- **Models**: Contains the data models.
  - `WeatherForecast.cs`: Defines the properties for a weather forecast.

- **Properties**: Contains application properties.
  - `launchSettings.json`: Settings for launching the application in different environments.

- **Configuration Files**:
  - `appsettings.json`: General configuration settings for the application.
  - `appsettings.Development.json`: Configuration settings specific to the development environment.

- **Program.cs**: The entry point of the application that configures and runs the web host.

- **Startup.cs**: Configures services and the application's request pipeline.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd my-dotnet-core-api
   ```

3. Restore the dependencies:
   ```
   dotnet restore
   ```

4. Run the application:
   ```
   dotnet run
   ```

## Usage

Once the application is running, you can access the weather forecast data by sending a GET request to the following endpoint:

```
GET /weatherforecast
```

This will return a list of weather forecasts in JSON format.