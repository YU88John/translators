import json
import yaml 

def json_to_yaml(json_string):
    try:
        # Parse the JSON input
        data = json.loads(json_string)

        # Convert the Python dictionary to YAML
        yaml_data = yaml.dump(data, default_flow_style=False)

        return yaml_data
    except Exception as e:
        return f"Error: {e}"

# Ask the user for JSON input
json_input = input("Enter your JSON data: ")

# Convert JSON to YAML
yaml_output = json_to_yaml(json_input)

print("\nYAML output:")
print(yaml_output)
