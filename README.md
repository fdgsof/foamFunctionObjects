Function object collection for OpenFOAM.

Use by including them into the controlDict in the functions section at the end. Example (if they are saved in the ./system directory)

```c++
functions
    {
        #include FOtest1
        #include FOtest2
    }
// ************************************************************************* //
```


Mostly tested with v2112 (ESI-branch).

