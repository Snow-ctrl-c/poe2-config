# Example POE 2 Config File

When setting the `renderer_type` config flag in the [POE Wiki guide](https://www.poewiki.net/wiki/Guide:Path_of_Exile_on_Mac_using_Windows_Client) sometimes the game will still use Vulkan and cause a crash. You can use the [my config](poe2_production_Config.ini) to get pass startup.

### Changing the Config

I think these tutorial flags, when set to `true`, will disable tutorials. You might want to change all of these to false if you're a _new player_.

```ini
[TUTORIAL_FLAGS]
FirstSkillGemTutorial_Gamepad=false
...
```
