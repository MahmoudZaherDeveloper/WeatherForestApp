# WeatherApp
A simple android app to hit API to get the Current weather and forecasts in your city. [Open Weather Map API](https://openweathermap.org/)


## Developed Features
1. Architecture MVI with [Mosby MVI library](https://github.com/sockeqwe/mosby)
       - Data (for models, database, API and preferences)
       - Presentation (for UI logic, with Mosby Mvi Presenter)
2. Dependency injection (with [Koin](https://insert-koin.io/))
3. Retrofit2 for server call 
4. Kotlin with RX 
5. Lifecycle - ViewModel
6. Auto update weather per 15 minutes with [Jetpack WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager)
7. Local data with [Room Persistence](https://developer.android.com/topic/libraries/architecture/room)

## Contributing
All pull requests are welcome, make sure to follow the contribution guidelines when you submit pull request.

1. Fork it!
2. Checkout the development branch: git checkout development
3. Create your feature branch: git checkout -b my-new-feature
4. Add your changes to the index: git add .
5. Commit your changes: git commit -m 'Add some feature'
6. Push to the branch: git push origin my-new-feature
7. Submit a pull request against the development branch
