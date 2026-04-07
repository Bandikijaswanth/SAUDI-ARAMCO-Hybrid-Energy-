# SAUDI-ARAMCO-Hybrid-Energy-
AIM

To implement a threshold-based energy management system for switching to charging mode.

PROCEDURE
Initialize the battery level
Define a critical battery threshold
Compare battery level with threshold
If battery < threshold, switch to charging mode
Otherwise, continue normal operation
Display the result
CODE
# Input value
battery = 18   # in percentage

# Threshold
threshold = 20

# Energy management logic
if battery < threshold:
    mode = "Charging Mode"
else:
    mode = "Operational Mode"

# Output
print(mode)
OUTPUT

Charging Mode

RESULT

The system switches to Charging Mode when the battery level drops below the threshold, ensuring continuous operation and energy safety.
