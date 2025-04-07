# Unity-Python-March-22nd-19th
March 22
Python: CSV parsing with csv.reader

Read lines, append to list, print subsets

March 23

Apple and bomb prefab spawn with Random.Range(-1, 2) for x, z positioning

Update() uses delta time to spawn objects at regular interval

March 26

Random.Range(int, int) => returns integer

Random.Range(float, float) => returns float

March 27

Used GetComponent<> to access another script's variables/methods

SetParameter(float span, float speed, int ratio) to manage game difficulty

Applied speed to falling item via:
item.GetComponent().dropSpeed = this.speed;

March 29

Web crawling concept

Parsing = extracting specific pattern from HTML with parser

March 30

Plane = 10x10 units

Cube scale of 1 = 1 unit, scale 20 = 20 units

Shader = defines how pixel color is computed based on input (like paint)

Texture = base sketch or drawing

Albedo = reflectiveness, defines base color of surface

Cube can look rotated using scale, not rotation

Rotation:
X = roll forward/backward
Y = rotate left/right (turning view)
Z = tilt side to side (like airplane roll)

March 31

Axis input system: lets you change key bindings from settings without changing code

Edit > Project Settings > InputManager:
-> Horizontal/Vertical axes (supports keyboard + joystick)
-> Input.GetAxis("Horizontal") handles both arrow keys and gamepad

Joystick returns values like 0.5 (analog input), not just -1/0/1

Script file name (PlayerController.cs) must match class name (PlayerController)

Prefab syncing:
-> After changing instance in scene, go to Inspector > Overrides > Apply All to update prefab

Random.Range(0, 3) returns 0, 1, 2 (int)

Random.Range(0f, 3f) returns float between 0.0 ~ 3.0

FindFirstObjectByType() = searches entire scene for the first object of a type
-> Should only be used in Start(), not Update(), because it's expensive

April 2

Instantiate(prefab, position, rotation)

transform.position = this object's position

transform.rotation = this object's rotation

LookAt(other.transform) = makes this object rotate to face the other
