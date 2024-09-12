To connect drone to python , open the window command , type in mode to see which port telemetry is using. Enusre you have the mavsdk server installed into the same directory 
that the command window. below is an example of how connecting to the drone should look.

cd C:\Users\samar\Downloads\mavsdk-windows-x64-release\bin

mavsdk_server_bin.exe serial://COM10:57600 -p 50051

ENSURE YOU ARE USING -p 50051 as this is the port mavsdk uses.

