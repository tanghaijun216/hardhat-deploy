@@ -1,23 +1,19 @@
{
  “ editor.formatOnSave”：是的，
  “ editor.defaultFormatter”：“ dbaeumer.vscode-eslint ”，
  “ [solidity] ”：{
    “ editor.defaultFormatter ”：“ esbenp.prettier-vscode”
  “ editor.defaultFormatter”：“ esbenp.prettier-vscode ”，
  “ editor.codeActionsOnSave ”：{
    “ source.fixAll ”：是
  }，
  “ solidity.linter”：“ solhint”，
  “ solidity.enableLocalNodeCompiler”：否，
  “ solidity.compileUsingRemoteVersion”：“ 0.7.1 + commit.f4a555b.Emscripten.clang”，
  “ solidity.packageDefaultDependenciesContractsDirectory”：“ src”，
  “ solidity.compileUsingRemoteVersion”：“ v0.7.1 + commit.f4a555be”，
  “ solidity.packageDefaultDependenciesContractsDirectory”：“”，
  “ solidity.enabledAsYouTypeCompilationErrorCheck”：是的，
  “ solidity.validationDelay”：1500，
  “ solidity.packageDefaultDependenciesDirectory”：“ node_modules”，
  “ editor.codeActionsOnSave”：{
    “ source.fixAll.eslint”：是
  }，
  “ [json]”：{
    “ editor.formatOnSave”：否，
    “ editor.codeActionsOnSave”：{}
  }，
  “ mochaExplorer.env”：{
    “ HARDHAT_CONFIG”：“ hardhat.config.ts”
    “ HARDHAT_CONFIG”：“ hardhat.config.ts”，
    “ HARDHAT_COMPILE”：“ true”
  }，
  “ mochaExplorer.require”：[“ ts-node / register / transpile-only”]
}
