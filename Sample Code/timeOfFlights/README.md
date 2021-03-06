# timeOfFlights

This sample shows how to code Misty to react when she detects an object within a certain distance of her range (outward-facing) time-of-flight sensors. You can use this sample as a template to customize your own reactions to time-of-flight events.

In this sample, we use two methods from Misty's JavaScript API to register for time-of-flight (`TimeOfFlight`) event messages. We use the `misty.RegisterEvent()` method to create a new event listener for messages from Misty's time-of-flight sensors, and we use the `misty.AddPropertyTest()` method to filter out event messages that don't match the criteria we set.

When Misty sends a `TimeOfFlight` event message, that message data gets passed into a callback function where we write the code that defines how the robot should respond.

You can run this code on your robot by uploading the files from this folder to Misty via the Skill Runner web tool. Alternately, refer to this code sample (or copy and paste it into your own skills) when working on similar functionality.
