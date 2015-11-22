
# Run the build
```docker run -d halzy/mosquitto-build```

Then get the .so file to include in another package:
```docker cp halzy/mosquitto-build:/build/mosquitto-auth-plug/auth-plug.so .```

Now you have the *auth-plug.so* file!
