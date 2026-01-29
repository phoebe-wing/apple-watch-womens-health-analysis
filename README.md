# Start Here
Which file to start in

# Want to build this project with your own data?
1. Download the iOS app Simple Health Export CSV by Eric Wolter (https://www.ericwolter.com/projects/apple-health-export/)
2. Open the app and allow to "Connect to Health App"
3. You'll need to export the following datasets:
    - Quantities: Body > AppleSleepingWristTemperature
    - Categories: Reproductive Health > MenstrualFlow
4. Import them into Jupyter under /data/raw
5. Ensure you have the correct libraries and versions as enumerated in requirements.txt installed: `pip install -r requirements.txt` 