# B1C4Planets

## Practice: Planet and Spaceships

Setup

```
mkdir -p ~/workspace/csharp/exercises/lists && cd $_
dotnet new console
```

##### Instructions

1. In the Main method, place the following code

```
List<string> planetList = new List<string>(){"Mercury", "Mars"};
```

2. `Add()` Jupiter and Saturn at the end of the list.
   Create another List that contains that last two planet of our solar system.
3. Combine the two lists by using `AddRange()`.
4. Use `Insert()` to add Earth, and Venus in the correct order.
5. Use `Add()` again to add Pluto to the end of the list.
6. Now that all the planets are in the list, slice the list using `GetRange()` in order to extract the rocky planets into a new list called rockyPlanets. The rocky planets will remain in the original planets list.
7. Being good amateur astronomers, we know that Pluto is now a dwarf planet, so use the `Remove()` method to eliminate it from the end of planetList.
