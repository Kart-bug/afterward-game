\---

name: godot-gdscript-style

description: Use when writing or editing GDScript or Godot scenes in this project. Defines naming, structure and style conventions.

\---



\# Godot / GDScript style



\- Target Godot 4.x, GDScript only.

\- File names: snake\_case (player\_controller.gd). Scene names match the script name (player\_controller.tscn).

\- Node names: PascalCase. Variables and functions: snake\_case. Constants: UPPER\_SNAKE\_CASE. Classes: PascalCase.

\- Use static typing where practical (var speed: float = 4.0).

\- Use @export for values the team may want to tweak in the editor.

\- Prefer signals over scripts reaching into each other's nodes.

\- One script = one job. Keep scripts short and commented.

\- Put scripts in scripts/, scenes in scenes/, assets in assets/.

\- Avoid global singletons (autoloads) unless clearly needed; ask first.

\- Use simple placeholder shapes and plain materials until the team approves final art.

\- Keep performance light: no expensive effects unless asked.

\- Do not add plugins or external dependencies without asking.

