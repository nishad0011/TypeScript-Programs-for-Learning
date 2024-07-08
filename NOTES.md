
TYPESCRIPT:
    INSTALL:
        npm i typescript -g

    update js file on saving ts:
        tsc main.ts -w

    create tsconfig.json:
        tsc --init

    structure:
        in tsconfig.json:
            "rootDir": "./src"
            "outDir": "./build/js", 

        start with:
            tsc -w

        Prevent running ts code with error:
            "noEmitOnError": true,