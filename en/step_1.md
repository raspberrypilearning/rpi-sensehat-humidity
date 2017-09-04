- In a Python file, enter the following code:

    ```python
    from sense_hat import SenseHat

    sense = SenseHat()
    sense.clear()

    humidity = sense.get_humidity()
    print(humidity)
    ```

    <iframe src="https://trinket.io/embed/python/cd35fdd905" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

- When you run the program, you should see something like this:

    ```bash
    34.6234588623
    ```

