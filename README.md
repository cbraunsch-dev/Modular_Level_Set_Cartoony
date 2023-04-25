# Cartoony Modular Level Set
A set of modules that can be combined to build a cartoony level

![Screenshot 2023-04-25 at 06 59 24](https://user-images.githubusercontent.com/41971262/234403147-2e5cb13c-12d3-4c64-982d-0d3c6414beb4.png)

![Screenshot 2023-04-25 at 07 00 11](https://user-images.githubusercontent.com/41971262/234403232-9ea8ffa7-38a5-403a-a27f-6fce604944c7.png)

![Screenshot 2023-04-25 at 07 00 00](https://user-images.githubusercontent.com/41971262/234403287-e49f74e5-c10d-4b14-9924-67b32381b7dd.png)

![image](https://user-images.githubusercontent.com/41971262/234405429-7d495ede-1315-4317-a077-90c858a3caa4.png)

Drag the models into unity (the FBX models) and snap them together using Unity's vertex snapping mode (hold down V and snap the objects together).

## Caveat
There are two minor issues with the following module:

![image](https://user-images.githubusercontent.com/41971262/234405825-7a6546d0-251d-4296-9b5a-0e97535816ad.png)

The first issue is that the vertical crease that connects the two walls has a radius that is too large. Note how the crease consists of 4 sections:

![image](https://user-images.githubusercontent.com/41971262/234406080-a3e5feaf-34ba-49d3-a9ea-d3367f8587fd.png)

The other modules with these vertical creases only have 2 sections as can be seen in this module:

![image](https://user-images.githubusercontent.com/41971262/234406419-9de3453c-8792-4ff2-bea7-da2f84b55dae.png)

This means that if you connect these two pieces, you will see that they don't lign up seamlessly:

![image](https://user-images.githubusercontent.com/41971262/234406703-ed26147c-97ce-4fd9-9634-f947a197ffc9.png)

The second issue is that there needs to be a mirrored version of this module. The texture should not be mirrored, however. Therefore, mirroring it in Unity is not the solution because that would mirror the texture as well.

One solution to these issues is to just create this asset anew in a separate Blender file and to mirror it as well. Then, UV map it and texture paint it.

