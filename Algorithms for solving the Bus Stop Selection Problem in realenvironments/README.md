The instances for this paper are organized in JSON files, using the following structure:

{
  "cityName": The name of the city,
  "instanceId": The ID of the instance being used,
  "students": [
    {
      "id": Student id,
      "streetPoint": GeoJSON with student street point,
      "educationType": Student education type,
      "distanceWalkedToGeometry": Total distance walked by the student from it's home to it's street point
    }
  ],
  "schools": [
    {
      "id": School id,
      "streetPoint": GeoJSON with school street point
    }
  ]
}
