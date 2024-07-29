# -Structural_design_pattern

Use Case 1: Adapter Pattern
Scenario: A media player application that can play different formats (e.g., MP3 and MP4). The existing media player only supports MP3 format, and we need to adapt it to also play MP4 format.
•	MediaPlayer Interface: Defines the method to play media.
•	MP3Player Class: Implements the MediaPlayer interface and supports playing MP3 files.
•	AdvancedMediaPlayer Interface and MP4Player Class: Provide additional functionality to play MP4 files.
•	MediaAdapter Class: Adapts the AdvancedMediaPlayer to the MediaPlayer interface.
•	AudioPlayer Class: Uses MediaAdapter to support both MP3 and MP4 formats.

Use Case 2: Decorator Pattern
Scenario: A coffee shop application where different types of coffee can have various add-ons (e.g., milk, sugar).
•	Coffee Interface: Defines the methods to get the description and cost of the coffee.
•	SimpleCoffee Class: Implements the Coffee interface and provides the base coffee functionality.
•	CoffeeDecorator Abstract Class: Implements the Coffee interface and serves as a base class for all decorators.
•	MilkDecorator and SugarDecorator Classes: Extend CoffeeDecorator to add specific functionalities (milk and sugar) to the coffee.

