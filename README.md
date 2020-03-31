
This is a project to demonstrate the TS errors in IntelliJ.

1. Open the project in IntelliJ
2. Open an integrated terminal in IntelliJ
3. Run `yarn` to install dependencies
4. Run `yarn start` to run project
5. Wait a couple seconds and you should get output like 
    ```
    Failed to compile.
    
    /private/tmp/SampleTsError/src/index.tsx
    TypeScript error in /private/tmp/SampleTsError/src/index.tsx(8,1):
    Type '"string"' is not assignable to type 'number'.  TS2322
    ```
6. I would like to click on the `/private/tmp/SampleTsError/src/index.tsx(8,1)` line and have
it jump to index.tsx:8, but right now it just jumps to line 1.