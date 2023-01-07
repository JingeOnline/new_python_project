Section "Device"
    Identifier "DummyDevice"
    Driver "dummy"
    VideoRam 256000
EndSection
 
Section "Screen"
    Identifier "DummyScreen"
    Device "DummyDevice"
    Monitor "DummyMonitor"
    DefaultDepth 24
    SubSection "Display"
        Depth 24
        Modes "1920x1080_60.0"
    EndSubSection
EndSection
 
Section "Monitor"
    Identifier "DummyMonitor"
    HorizSync 30-70
    VertRefresh 50-75
    ModeLine "1920x1080" 148.50 1920 2448 2492 2640 1080 1084 1089 1125 +Hsync +Vsync
EndSection
