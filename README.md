# Unity-Cheat-Sheet

## In Unity

## In Scripts

### Variables

Visibility of Variable
public : visible in inspector and enable modification of variable from other script.
public static : same as public but can now be called from all scripts, but there can be only one instance of it.
[HideInInspector] public : cannot be seen in inspector, can be modified from other script.

private : not visible in inspector and can only be modified from within the script.
[SerializedField] private : is now visible in Inspector but cannot be modified from other script


