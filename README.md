#**Name That Landmark**

#About

Name That Landmark is a game built with the ArcGIS API for JavaScript. The aim of the game is to guess a location from aerial imagery by scratching off a panel obscuring it. The more that is scratched the less a player scores. A player also scores less points the longer they take to name the location.

#Sample
The sample is build with a world landmark dataset and can be viewed here.

#Configuring
Editing the config.json file allows you to specify:
1. Polygon feature service containing location content for the game
2. Editable point feature service for leaderboard data (must have 'Name' and 'Score' fields)
3. Field in the polygon feature service that contains the location name
4. Object ID field in the polygon feature service
5. Amount of time allowed for each round
6. Number of rounds

#Issues

Find a bug or want to request a new feature? Please let us know by submitting an issue.

#Licensing

Copyright 2015 ESRI (UK) Limited

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the Licence.