# WSN_PUF
Scyther Analysis.
Verify the scheme with Scyther.
Use Scyther 1.3 and Python 2.
'Sink_User.spdl' verify authentication between sink and user node. Use bound 3. Default bound 5 may take tool long time.
'Sink_Sensor.spdl' verify the group key delivery from sink to sensor node. Works fine with default bound 5.
'Sink_Sensor_authentication.spdl' verify the group key delivery from sink to senosr node, considering the authentication phase. Use bound 3.
