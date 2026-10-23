# Pygold Studio

**Create worlds with ease and test** them out using this *mini-engine* built with Python and the Ursina Engine!

## Install

1. You need to have the Ursina engine downloaded; you can do this using this command: **```pip install ursina```**
2. Have Python 3.12 or higher installed

> [!NOTE]
> I havent tested it on other operating systems; I recommend trying it on Windows.

## How to use it

You can load or export a JSON file using **"Load"** and **"Export"**, and you can also test your games by clicking **"Run Test"** in the toolbar. Create parts using **"Insert Part"** and modify them by clicking on their position and size parameters *(you can even change textures and colors!)*.

**You can use this JSON to start testing everything!**:
```json
{"world": [{"name": "baseplate", "type": "cube", "x": 0.0, "y": -0.5, "z": 0.0, "sx": 20.0, "sy": 1.0, "sz": 20.0, "color": "#3a9048", "texture": "grass.png"}, {"name": "p1", "type": "cube", "x": 0.0, "y": -0.20000000298023224, "z": 0.0, "sx": 2.0, "sy": 1.0, "sz": 2.0, "color": "#8d8d8d", "texture": "brick.png"}, {"name": "p2", "type": "cube", "x": 0.0, "y": 0.800000011920929, "z": 0.0, "sx": 1.399999976158142, "sy": 1.0, "sz": 1.399999976158142, "color": "#8d8d8d", "texture": "brick.png"}, {"name": "p3", "type": "cube", "x": 0.0, "y": 1.7999999523162842, "z": 0.0, "sx": 1.2000000476837158, "sy": 1.0, "sz": 1.2000000476837158, "color": "#8d8d8d", "texture": "brick.png"}, {"name": "blaze", "type": "cube", "x": 0.0, "y": 2.799999952316284, "z": 0.0, "sx": 0.20000000298023224, "sy": 1.0, "sz": 0.20000000298023224, "color": "#ffff00", "texture": "white_cube.png"}]}
```
