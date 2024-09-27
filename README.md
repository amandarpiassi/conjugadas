This Python code calculates the closest conjugate station for any given magnetic station, based on the same L-shell. The conjugate station is the point on the opposite side of the magnetic field line, typically located in the opposite hemisphere. This tool is useful for geomagnetic and ionospheric studies, as it helps identify stations that share the same magnetic flux tube.

Features:
Converts geographic coordinates (latitude, longitude, altitude) of a magnetic station to geomagnetic coordinates using the AACGM-v2 model.
Computes the conjugate geomagnetic point by inverting the geomagnetic latitude.
Converts the conjugate point back to geographic coordinates.
Calculates the L-shell for both the original station and its conjugate, providing information on their position within the Earth's magnetic field.
Finds the closest station to the conjugate point based on the geodesic distance between stations.
Requirements:
Python 3.x
aacgmv2 library for geomagnetic conversions.
geopy library for calculating geodesic distances.
How to Use:
Clone this repository.
Install the required libraries:
bash

pip install aacgmv2 geopy
Add or modify the list of stations in the code as needed.
Run the script to find the closest conjugate station for any magnetic station.

EXEMPLE

The code will take a magnetic station (e.g., KHB in Russia), compute its conjugate point, and return the closest station to that conjugate point, along with the L-shell values for both stations.


%%


Este código Python calcula a estação conjugada mais próxima para uma determinada estação magnética, com base no mesmo L-shell. A estação conjugada é o ponto no lado oposto da linha de campo magnético, normalmente localizado no hemisfério oposto. Esta ferramenta é útil para estudos geomagnéticos e ionosféricos, pois ajuda a identificar estações que compartilham o mesmo tubo de fluxo magnético.

Funcionalidades:
Converte coordenadas geográficas (latitude, longitude, altitude) de uma estação magnética para coordenadas geomagnéticas usando o modelo AACGM-v2.
Calcula o ponto geomagnético conjugado invertendo a latitude geomagnética.
Converte o ponto conjugado de volta para coordenadas geográficas.
Calcula o L-shell para ambas as estações, original e conjugada, fornecendo informações sobre sua posição no campo magnético da Terra.
Encontra a estação mais próxima ao ponto conjugado com base na distância geodésica entre as estações.
Requisitos:
Python 3.x
Biblioteca aacgmv2 para conversões geomagnéticas.
Biblioteca geopy para calcular distâncias geodésicas.
Como Usar:
Clone este repositório.
Instale as bibliotecas necessárias:


pip install aacgmv2 geopy
Adicione ou modifique a lista de estações no código conforme necessário.
Execute o script para encontrar a estação conjugada mais próxima de qualquer estação magnética.
