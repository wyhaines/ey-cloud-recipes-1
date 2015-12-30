Tries to read /tmp/do-not-fail-chef

If the file exists, it won't fail. If the file doesn't exist, the recipe will
throw an error, and the chef run will fail.