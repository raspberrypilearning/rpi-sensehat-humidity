- In a Python file, enter the following code:

    ```python
    from sense_hat import SenseHat

    sense = SenseHat()
    sense.clear()

    humidity = sense.get_humidity()
    print(humidity)
    ```

    <iframe src="https://editor.raspberrypi.org/en/embed/viewer/rpi-sensehat-humidity-example" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

    [Open this code in the Code Editor](https://editor.raspberrypi.org/en/projects/rpi-sensehat-humidity-example){:target="_blank"}

- When you run the program, you should see something like this:

    ```bash
    34.6234588623
    ```

