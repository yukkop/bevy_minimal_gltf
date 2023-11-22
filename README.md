# bevy_minimal_gltf

This repository contains `bevy_minimal_gltf`, a simplified version of `bevy_gltf` version 0.12.0. The primary modification in this version is the removal of all material and shader components, focusing solely on mesh loading. This makes it an ideal choice for projects that require only the mesh loading capabilities of the original `bevy_gltf` without the overhead of additional rendering features.

## Features

- **Mesh Loading:** Retains the mesh loading functionality of `bevy_gltf` 0.12.0.
- **Simplified:** Removes all material and shader components for a lighter, more focused usage.

## Usage

The usage of `bevy_minimal_gltf` is similar to the original `bevy_gltf`. After including this crate in your project, you can load GLTF assets as meshes in your Bevy application. Refer to the original `bevy_gltf` documentation for more details on loading GLTF files, keeping in mind that materials and shaders are not supported in this version.

## Contributions

Contributions are welcome, especially in areas that enhance the mesh loading capabilities or optimize the existing codebase.

## License

`bevy_minimal_gltf` is licensed under the same terms as the original [bevy](https://github.com/bevyengine/bevy), ensuring compatibility and ease of integration with Bevy projects.