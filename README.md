



This plug-in is a library that can use clusters in react-leaflet.


This is a working version of react-leaflet-markercluster in "react-leaflet": "2.6.3", "leaflet": "1.6.0"


[![sample](https://raw.githubusercontent.com/Leaflet/Leaflet.markercluster/HEAD/example/map.png "sample")](https://raw.githubusercontent.com/Leaflet/Leaflet.markercluster/HEAD/example/map.png "sample")

### usage ####
``
import MarkerClusterGroup from 'leaflet-make-cluster-group'``

	<MarkerClusterGroup>

                                <Marker

                                    position={[37.2411, 127.1776]}
                                    icon={cell_phone}

                                >
                                    <Popup>용인 jessica.</Popup>
                                </Marker>
                                <Marker
                                    position={[37.5665, 126.9780]}
                                    icon={cell_phone}
                                >
                                    <Popup>seoul WeWork.</Popup>
                                </Marker>
                                <Marker

                                    position={[37.3947, 127.1112]}
                                    icon={cell_phone}

                                >
                                    <Popup>성남 고경준.</Popup>
                                </Marker>
	</MarkerClusterGroup>
	
	======
	made with love ❤

