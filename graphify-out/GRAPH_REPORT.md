# Graph Report - forks/Ghost-CLI  (2026-08-09)

## Corpus Check
- 225 files · ~140,023 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 1656 nodes · 2041 edges · 198 communities (132 shown, 66 thin omitted)
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 68 edges (avg confidence: 0.58)
- Token cost: 84,645 input · 0 output

## Community Hubs (Navigation)
- API Auth Strategies
- Agent Guide & Test Deps
- UID/Systemd Extension Utils
- UI Renderer Base
- ACME/SSL Cert Generation
- Process Manager Base
- Stop Command
- Root Dev/Test Dependencies
- MySQL Extension
- Pretty Log Stream
- CLI Error Base
- Bootstrap & Argv Parsing
- Valid Install Check
- Nginx Extension Manifest
- Directory Permission Checks
- Nginx Extension Tests
- Binary Dependency Checks
- System Checks Index
- System Instance Registry
- Renderer Rendering Logic
- URL Prompt Utils
- Install Dependencies
- CLI Package Manifest
- ACME Extension Tests
- Base Command Class
- Error Handling & Memory Checks
- Config Error & Parse Options
- Extension Base Class
- Export Parsing
- Root Package Dependencies
- MySQL System Check
- System Stack Check
- System Instance Model
- Root User Check
- Config Utils
- Update Command Tests
- Logged-In User Owner Check
- Python Setuptools Check
- Proxy Agent Utils
- Log Command Tests
- Doctor Command
- Free Space Check
- Setup Command
- Pre-Install Checks
- Process Validity Tests
- Command Framework Tests
- Setup Command Tests
- UI Index Tests
- ESLint Root Config
- Systemd Extension Manifest
- Logged-In User Check
- Doctor/Install Command Index
- DB Migrations Setup
- Backup Task
- Deprecation Checks
- pnpm Process Utils
- Port Polling
- Renovate Config
- Uninstall Command Tests
- Instance Model Tests
- Install Dependencies Tests
- MySQL Extension Manifest
- Migrations Test Fixtures
- Permission Checks
- Content Folder Permissions
- pnpm Checks
- Config Validation
- Update Command
- Update Command Methods
- Config Options Schema
- Structure Setup Tests
- Install Command Tests
- Start Command Tests
- Doctor Command Tests
- Systemd Process Manager Tests
- List Command
- Run Command
- Migrator
- Process Manager Tests
- Options Tests
- Parse Options Tests
- Tasks Tests
- Test Folder Utils
- Nginx Migrations
- Config Command
- File Permissions Check
- Folder Permissions Check
- Logged-In Ghost User Check
- Install Command
- Release Notes
- Bootstrap Tests
- DB Migrations Tests
- UI Tests
- Local Process Manager Tests
- pnpm Process Tests
- Pre-Checks Tests
- Yarn Process Tests
- Stream Utils
- MySQL Test ESLint Config
- MySQL Extension Tests
- Nginx Test ESLint Config
- Systemd Test ESLint Config
- Yarn Process Manager
- Ghost User Detection
- npm Scripts
- Test ESLint Config
- Config Command Tests
- Logged-In Ghost User Tests
- Node Version Check Tests
- Config Validation Tests
- Run Command Tests
- Extension Base Tests
- Migrator Tests
- Ghost User Detection Tests
- Log Command
- Setup Command Methods
- Instance Config Model
- Repo File Layout
- Directory Check Tests
- Folder Permission Tests
- Export Command Tests
- Import Command Tests
- Stop Command Tests
- Test Instance Helper
- Config Subcommand Tests
- Linux Process Manager Tests
- Backup Command
- Buster Command
- Check-Update Command
- Memory Check
- Export Command
- Import Command
- Migrate Command
- Restart Command
- Uninstall Command
- Version Command
- NYC Coverage Config
- Check-Update Tests
- Doctor Command Index Tests
- Migrate Command Tests
- Version Command Tests
- Dir-Is-Empty Tests
- Extension Discovery Tests
- UID Lookup Tests
- Linux Process Manager
- Dir-Is-Empty Util
- Package Keywords
- Package Repository Metadata
- Buster Command Tests
- Restart Command Tests
- Config Utils Tests
- boxen dependency
- chalk dependency
- cli-table3 dependency
- debug dependency
- decompress dependency
- execa dependency
- find-plugins dependency
- fkill dependency
- form-data dependency
- generate-password dependency
- Stale Issues Workflow
- global-modules dependency
- got dependency
- https-proxy-agent dependency
- inquirer dependency
- jsonwebtoken dependency
- latest-version dependency
- listr dependency
- lodash dependency
- moment dependency
- mysql2 dependency
- ora dependency
- package-json dependency
- path-is-root dependency
- portfinder dependency
- prettyjson dependency
- proxy-from-env dependency
- read-last-lines dependency
- replace-in-file dependency
- rxjs dependency
- semver dependency
- shasum dependency
- stat-mode dependency
- symlink-or-copy dependency
- systeminformation dependency
- tail dependency
- tough-cookie dependency
- @tryghost/zip dependency
- validator dependency
- which dependency
- yargs dependency
- yarn dependency
- Invalid Command Fixture
- Mocha Root Hooks
- Needed Migrations Tests

## God Nodes (most connected - your core abstractions)
1. `SystemError` - 30 edges
2. `Instance` - 21 edges
3. `System` - 18 edges
4. `UI` - 17 edges
5. `Ghost-CLI Agent Guide (AGENTS.md)` - 15 edges
6. `MySQLExtension` - 14 edges
7. `ProcessManager` - 13 edges
8. `SystemdProcessManager` - 12 edges
9. `CliError` - 12 edges
10. `UpdateCommand` - 9 edges

## Surprising Connections (you probably didn't know these)
- `Ghost-CLI Agent Guide (CLAUDE.md)` --semantically_similar_to--> `Ghost-CLI Agent Guide (AGENTS.md)`  [INFERRED] [semantically similar]
  CLAUDE.md → AGENTS.md
- `standard-version (commit guideline tool)` --semantically_similar_to--> `Conventional Commit Message Format`  [INFERRED] [semantically similar]
  CHANGELOG.md → .github/CONTRIBUTING.md
- `Added pnpm support alongside yarn (v1.29.0)` --rationale_for--> `Ghost-CLI Agent Guide (AGENTS.md)`  [INFERRED]
  CHANGELOG.md → AGENTS.md
- `pnpm Workspace Config` --conceptually_related_to--> `Ghost-CLI Agent Guide (AGENTS.md)`  [INFERRED]
  pnpm-workspace.yaml → AGENTS.md
- `nginx Built-in Extension` --conceptually_related_to--> `nginx Fixture: SSL via acme.sh/Let's Encrypt`  [INFERRED]
  AGENTS.md → extensions/nginx/test/fixtures/old-ssl-with-le.txt

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Ghost-CLI CI Workflow Pipeline** — github_workflows_e2e_test_e2e_tests_workflow, github_workflows_local_e2e_test_local_e2e_tests_workflow, github_workflows_unit_test_unit_tests_workflow, github_workflows_publish_publish_workflow, github_workflows_stale_stale_workflow [INFERRED 0.85]
- **Ghost-CLI Testing Stack** — agents_mocha, agents_chai, agents_sinon, agents_proxyquire, agents_nock [INFERRED 0.85]
- **Standard CI Checkout/Setup Action Pattern** — github_workflows_e2e_test_action_checkout, github_workflows_e2e_test_action_pnpm_setup, github_workflows_e2e_test_action_setup_node [INFERRED 0.85]

## Communities (198 total, 66 thin omitted)

### Community 0 - "API Auth Strategies"
Cohesion: 0.07
Nodes (45): {Cookie}, get, got, sessionAuthStrategy(), tokenAuthStrategy(), v1AuthStrategy(), bases, downloadContentExport() (+37 more)

### Community 1 - "Agent Guide & Test Deps"
Cohesion: 0.06
Nodes (47): Ghost-CLI Agent Guide (AGENTS.md), Chai (assertion library), mysql Built-in Extension, nginx Built-in Extension, systemd Built-in Extension, Mocha (test framework), Nock (HTTP mocking), Proxyquire (dependency stubbing) (+39 more)

### Community 2 - "UID/Systemd Extension Utils"
Cohesion: 0.06
Nodes (22): execa, fs, path, {Extension, errors}, fs, getUid, path, SystemdExtension (+14 more)

### Community 3 - "UI Renderer Base"
Cohesion: 0.09
Nodes (21): chalk, createRendererClass, defaultOptions, errors, execa, getDefault(), hasDefault(), inquirer (+13 more)

### Community 4 - "ACME/SSL Cert Generation"
Cohesion: 0.08
Nodes (23): download, {errors: {CliError, ProcessError, SystemError}}, {errorWrapper}, fs, got, install(), isInstalled(), os (+15 more)

### Community 5 - "Process Manager Base"
Cohesion: 0.08
Nodes (7): ProcessManager, requiredMethods, fs, LocalProcess, path, ProcessManager, TODO: verify windows outputs same error message as mac/linux

### Community 6 - "Stop Command"
Cohesion: 0.09
Nodes (3): Command, StopCommand, Instance

### Community 7 - "Root Dev/Test Dependencies"
Cohesion: 0.08
Nodes (25): chai, chai-as-promised, eslint, eslint-plugin-ghost, has-ansi, mocha, nock, nyc (+17 more)

### Community 8 - "MySQL Extension"
Cohesion: 0.16
Nodes (11): {Extension, errors}, generator, isMySQL8(), isUnsupportedMySQL(), localhostAliases, mysql, MySQLExtension, omit (+3 more)

### Community 9 - "Pretty Log Stream"
Cohesion: 0.12
Nodes (18): chalk, each, isArray, isEmpty, isObject, isString, levelColors, levels (+10 more)

### Community 10 - "CLI Error Base"
Cohesion: 0.10
Nodes (13): CliError, chalk, each, showDetails(), {CliError}, proxyquire, sinon, {CliError, SystemError} (+5 more)

### Community 11 - "Bootstrap & Argv Parsing"
Cohesion: 0.09
Nodes (19): argv, bootstrap, yargs, abbrev, bootstrap, Command, createDebug, debug (+11 more)

### Community 12 - "Valid Install Check"
Cohesion: 0.12
Nodes (16): chalk, fs, path, chalk, checkValidInstall, debug, die(), {dirname} (+8 more)

### Community 13 - "Nginx Extension Manifest"
Cohesion: 0.10
Nodes (19): description, ghost-cli, after, name, options, ghost-cli-extension, keywords, main (+11 more)

### Community 14 - "Directory Permission Checks"
Cohesion: 0.11
Nodes (17): errors, fs, isRoot, Mode, path, chalk, checkDirectoryAndAbove, constants (+9 more)

### Community 15 - "Nginx Extension Tests"
Cohesion: 0.15
Nodes (13): addStubs(), configStub, {errors, Extension}, fs, migrations, Nginx, Promise, proxyNginx() (+5 more)

### Community 16 - "Binary Dependency Checks"
Cohesion: 0.12
Nodes (12): chalk, {SystemError}, SystemError, check, {expect}, semver, sinon, {SystemError} (+4 more)

### Community 17 - "System Checks Index"
Cohesion: 0.12
Nodes (16): binaryDeps, checkMemory, contentFolder, filePermissions, folderPermissions, freeSpace, installFolderPermissions, loggedInGhostUser (+8 more)

### Community 19 - "Renderer Rendering Logic"
Cohesion: 0.14
Nodes (8): chalk, defaultOptions, ora, Renderer, createRenderer, {expect}, sinon, {stripVTControlCharacters: stripAnsi}

### Community 20 - "URL Prompt Utils"
Cohesion: 0.17
Nodes (12): path, {validate: validateUrl, ensureProtocol}, ensureProtocol(), isCustomDomain(), {isURL}, validate(), Config, {expect} (+4 more)

### Community 21 - "Install Dependencies"
Cohesion: 0.12
Nodes (14): chalk, {CliError, SystemError}, cliPackage, decompress, download, fs, getProxyAgent, packageInfo (+6 more)

### Community 22 - "CLI Package Manifest"
Cohesion: 0.12
Nodes (15): author, bin, ghost, bugs, contributors, description, engines, node (+7 more)

### Community 23 - "ACME Extension Tests"
Cohesion: 0.13
Nodes (8): cli, proxyquire, sinon, path, rootPath, cli, cli, TestValidCommand

### Community 24 - "Base Command Class"
Cohesion: 0.21
Nodes (8): Command, createDebug, debug, each, kebabCase, NOTE: we disable recursive searching when the cwd is supplied, System, UI

### Community 25 - "Error Handling & Memory Checks"
Cohesion: 0.14
Nodes (10): chalk, TODO: we receive all possible properties now, except the excluded ones above, errors, sinon, sysinfo, errors, {stripVTControlCharacters: stripAnsi}, errors (+2 more)

### Community 26 - "Config Error & Parse Options"
Cohesion: 0.14
Nodes (8): ConfigError, getPrompts, parseOptions, {ConfigError}, isFunction, options, Promise, url

### Community 27 - "Extension Base Class"
Cohesion: 0.15
Nodes (8): Extension, fs, mapValues, os, path, TODO: currently this returns an instance of the base class only if, Extension, TestExtension

### Community 28 - "Export Parsing"
Cohesion: 0.16
Nodes (12): find, fs, get, parse(), semver, {SystemError}, {expect}, fs (+4 more)

### Community 29 - "Root Package Dependencies"
Cohesion: 0.15
Nodes (13): abbrev, bluebird, download, fs-extra, ini, log-symbols, dependencies, abbrev (+5 more)

### Community 30 - "MySQL System Check"
Cohesion: 0.17
Nodes (10): chalk, mysqlCheck(), mysqlIsRunning(), sysinfo, {SystemError}, configStub, mysqlCheck, sinon (+2 more)

### Community 31 - "System Stack Check"
Cohesion: 0.18
Nodes (11): chalk, checkSystem(), hasService(), sysinfo, {SystemError}, systemStack(), {expect}, sinon (+3 more)

### Community 32 - "System Instance Model"
Cohesion: 0.17
Nodes (10): Config, Extension, findKey, fs, Instance, os, path, ProcessManager (+2 more)

### Community 33 - "Root User Check"
Cohesion: 0.17
Nodes (11): chalk, checkRootUser(), fs, isRootInstall(), os, TODO: remove this 4 versions after 1.5.0, TODO: remove this 4 versions after 1.5.0, checkRootUser (+3 more)

### Community 34 - "Config Utils"
Cohesion: 0.21
Nodes (6): Config, fs, _get, _has, isPlainObject, _set

### Community 35 - "Update Command Tests"
Cohesion: 0.15
Nodes (10): Command, configStub, errors, fs, Instance, path, Promise, proxyquire (+2 more)

### Community 36 - "Logged-In User Owner Check"
Cohesion: 0.17
Nodes (9): chalk, errors, fs, path, TODO: switch to require('os').userInfo() and output username in errors, errors, fs, loggedInUserOwner (+1 more)

### Community 37 - "Python Setuptools Check"
Cohesion: 0.23
Nodes (9): checkPython3(), checkSetuptools(), execa, pythonSetuptoolsCheck(), semver, {SystemError}, errors, proxyquire (+1 more)

### Community 38 - "Proxy Agent Utils"
Cohesion: 0.17
Nodes (10): {getProxyForUrl}, {CliError, SystemError}, cliPackage, decompress, fs, getProxyAgent, packageJson, path (+2 more)

### Community 39 - "Log Command Tests"
Cohesion: 0.18
Nodes (8): defaultInstance, defaultSystem, Errors, PrettyStream, proxyLog(), proxyquire, sinon, Tail

### Community 40 - "Doctor Command"
Cohesion: 0.22
Nodes (10): chalk, checkNodeVersion(), {errors}, execa, fs, get, ini, path (+2 more)

### Community 41 - "Free Space Check"
Cohesion: 0.18
Nodes (8): TODO: maybe throw a warning of some sort here?, sysinfo, {SystemError}, check, {expect}, sinon, sysinfo, {SystemError}

### Community 42 - "Setup Command"
Cohesion: 0.18
Nodes (7): Command, options, path, StartCommand, Command, DoctorCommand, StartCommand

### Community 43 - "Pre-Install Checks"
Cohesion: 0.22
Nodes (9): configstore, fs, getProxyAgent, latestVersion, os, path, pkg, semver (+1 more)

### Community 44 - "Process Validity Tests"
Cohesion: 0.18
Nodes (6): cli, Config, Instance, os, proxyquire, sinon

### Community 45 - "Command Framework Tests"
Cohesion: 0.18
Nodes (6): BadCommand, proxyquire, ShortCircuit, sinon, Test2Command, TestCommand

### Community 46 - "Setup Command Tests"
Cohesion: 0.22
Nodes (10): configStub, {expect}, getStartTask(), getTasks(), path, proxyquire, SetupCommand, sinon (+2 more)

### Community 47 - "UI Index Tests"
Cohesion: 0.18
Nodes (10): chalk, EventEmitter, execa, {expect}, hasAnsi, logSymbols, proxyquire, sinon (+2 more)

### Community 48 - "ESLint Root Config"
Cohesion: 0.20
Nodes (9): extends, ghost, parserOptions, ecmaVersion, plugins, rules, no-console, off (+1 more)

### Community 49 - "Systemd Extension Manifest"
Cohesion: 0.20
Nodes (9): ghost-cli, after, process-managers, ghost-cli-extension, keywords, main, name, systemd (+1 more)

### Community 50 - "Logged-In User Check"
Cohesion: 0.20
Nodes (7): chalk, errors, ghostUser, errors, ghostUser, loggedInUser, sinon

### Community 51 - "Doctor/Install Command Index"
Cohesion: 0.20
Nodes (7): Command, DoctorCommand, Command, DoctorCommand, fs, path, SetupCommand

### Community 52 - "DB Migrations Setup"
Cohesion: 0.24
Nodes (7): ensureFolder(), ensureMediaFileAndPublicFolders(), ensureSettingsFolder(), path, coreMigrations, flatten, semver

### Community 53 - "Backup Task"
Cohesion: 0.22
Nodes (8): copyFiles(), debug, {exportTask}, fs, ghostUser, path, {ProcessError}, zip

### Community 54 - "Deprecation Checks"
Cohesion: 0.36
Nodes (9): boxen, chalk, databaseDeprecated(), debug, deprecationChecks(), ghostDeprecated(), nodeDeprecated(), Promise (+1 more)

### Community 55 - "pnpm Process Utils"
Cohesion: 0.27
Nodes (9): chalk, execa, isCorepackSignatureError(), isReadonlyStoreError(), {Observable}, {ProcessError, SystemError}, runPnpm(), toPnpmError() (+1 more)

### Community 56 - "Port Polling"
Cohesion: 0.22
Nodes (7): errors, getNodeVersion(), useNetServer(), util, net, portPolling, sinon

### Community 57 - "Renovate Config"
Cohesion: 0.20
Nodes (9): cli-table3, github>tryghost/renovate-config, :semanticCommitTypeAll(chore), standard-version, validator, extends, ignoreDeps, minimumReleaseAge (+1 more)

### Community 58 - "Uninstall Command Tests"
Cohesion: 0.22
Nodes (8): createInstance(), fileList, fs, proxyquire, sinon, System, UI, UninstallCommand

### Community 59 - "Instance Model Tests"
Cohesion: 0.22
Nodes (9): Config, createConfigStub, {expect}, fs, Instance, ProcessManager, {setupTestFolder}, sinon (+1 more)

### Community 60 - "Install Dependencies Tests"
Cohesion: 0.20
Nodes (9): errors, fs, fsExtraResolved, {Observable, isObservable}, path, Promise, proxyquire, {setupTestFolder, cleanupTestFolders} (+1 more)

### Community 61 - "MySQL Extension Manifest"
Cohesion: 0.22
Nodes (8): description, ghost-cli, before, ghost-cli-extension, keywords, main, name, version

### Community 62 - "Migrations Test Fixtures"
Cohesion: 0.22
Nodes (8): cli, context, fs, oldSslWithLe, path, proxyquire, sinon, sslWithoutLe

### Community 63 - "Permission Checks"
Cohesion: 0.22
Nodes (7): chalk, errors, execa, checkPermissions, errors, execa, sinon

### Community 64 - "Content Folder Permissions"
Cohesion: 0.22
Nodes (7): checkPermissions, ghostUser, path, contentFolderPermissions, errors, execa, sinon

### Community 65 - "pnpm Checks"
Cohesion: 0.33
Nodes (7): chalk, checkCorepack(), checkPnpm(), execa, pnpmCheck(), semver, {SystemError}

### Community 66 - "Config Validation"
Cohesion: 0.25
Nodes (8): Config, errors, filter, get, options, path, Promise, validateConfig()

### Community 67 - "Update Command"
Cohesion: 0.22
Nodes (8): Command, DoctorCommand, fs, {GhostError}, ghostUser, path, TODO: add meaningful update checks after this task, GhostError

### Community 69 - "Config Options Schema"
Cohesion: 0.22
Nodes (8): knownMailServices, knownMailTransports, path, portfinder, toString, url, urlUtils, validator

### Community 70 - "Structure Setup Tests"
Cohesion: 0.22
Nodes (7): fs, path, ensureStructure, fs, path, {setupTestFolder, cleanupTestFolders}, sinon

### Community 71 - "Install Command Tests"
Cohesion: 0.22
Nodes (8): Command, errors, {expect}, fs, path, Promise, proxyquire, sinon

### Community 72 - "Start Command Tests"
Cohesion: 0.25
Nodes (8): createConfigStub, {expect}, getStubs(), Instance, proxyquire, sinon, System, UI

### Community 73 - "Doctor Command Tests"
Cohesion: 0.25
Nodes (7): checkUnitFile(), {checkUnitFile, checkNodeVersion}, {errors}, execa, {expect}, fs, sinon

### Community 74 - "Systemd Process Manager Tests"
Cohesion: 0.29
Nodes (7): configStub, errors, instance, makeSystemd(), proxyquire, sinon, Systemd

### Community 75 - "List Command"
Cohesion: 0.25
Nodes (5): Command, LsCommand, LsCommand, sinon, {stripVTControlCharacters: stripAnsi}

### Community 76 - "Run Command"
Cohesion: 0.32
Nodes (3): Command, RunCommand, semver

### Community 77 - "Migrator"
Cohesion: 0.39
Nodes (7): errorHandler(), errors, execa, ghostUser, migrate(), path, rollback()

### Community 78 - "Process Manager Tests"
Cohesion: 0.25
Nodes (4): getConfigStub, proxyquire, sinon, TestProcess

### Community 79 - "Options Tests"
Cohesion: 0.25
Nodes (7): {expect}, options, path, Promise, proxyquire, sinon, urlUtils

### Community 80 - "Parse Options Tests"
Cohesion: 0.29
Nodes (6): Config, {ConfigError}, {expect}, fake(), proxyquire, sinon

### Community 81 - "Tasks Tests"
Cohesion: 0.25
Nodes (7): createConfigStub, {expect}, Promise, proxyquire, sinon, {SystemError}, {TOKEN_AUTH_MIN_VERSION}

### Community 82 - "Test Folder Utils"
Cohesion: 0.29
Nodes (7): builtin, currentTestFolders, fs, isObject, path, setupTestFolder(), tmp

### Community 83 - "Nginx Migrations"
Cohesion: 0.29
Nodes (5): cli, fs, os, path, url

### Community 84 - "Config Command"
Cohesion: 0.29
Nodes (3): Command, ConfigCommand, options

### Community 85 - "File Permissions Check"
Cohesion: 0.29
Nodes (5): checkPermissions, errors, execa, filePermissions, sinon

### Community 86 - "Folder Permissions Check"
Cohesion: 0.29
Nodes (5): checkPermissions, errors, execa, folderPermissions, sinon

### Community 87 - "Logged-In Ghost User Check"
Cohesion: 0.29
Nodes (5): chalk, errors, fs, ghostUser, path

### Community 89 - "Release Notes"
Cohesion: 0.29
Nodes (4): {expect}, got, runTask, sinon

### Community 90 - "Bootstrap Tests"
Cohesion: 0.29
Nodes (6): path, proxyquire, {setupTestFolder, cleanupTestFolders}, sinon, yargs, cleanupTestFolders()

### Community 91 - "DB Migrations Tests"
Cohesion: 0.29
Nodes (6): createConfig, {expect}, fs, ghostUser, migrations, sinon

### Community 92 - "UI Tests"
Cohesion: 0.29
Nodes (5): configStub, proxyquire, sinon, {stripVTControlCharacters: stripAnsi}, sinon

### Community 93 - "Local Process Manager Tests"
Cohesion: 0.29
Nodes (6): childProcess, errors, fs, os, proxyquire, sinon

### Community 94 - "pnpm Process Tests"
Cohesion: 0.33
Nodes (6): {getReadableStream}, {isObservable}, {ProcessError, SystemError}, proxyquire, setup(), sinon

### Community 95 - "Pre-Checks Tests"
Cohesion: 0.33
Nodes (6): {expect}, fs, load(), os, proxyquire, sinon

### Community 96 - "Yarn Process Tests"
Cohesion: 0.33
Nodes (6): {getReadableStream}, {isObservable}, {ProcessError}, proxyquire, setup(), sinon

### Community 97 - "Stream Utils"
Cohesion: 0.33
Nodes (4): isString, stream, streamUtils, writeWrap()

### Community 98 - "MySQL Test ESLint Config"
Cohesion: 0.33
Nodes (5): env, mocha, rules, func-names, prefer-arrow-callback

### Community 99 - "MySQL Extension Tests"
Cohesion: 0.33
Nodes (5): configStub, errors, proxyquire, semver, sinon

### Community 100 - "Nginx Test ESLint Config"
Cohesion: 0.33
Nodes (5): env, mocha, rules, func-names, prefer-arrow-callback

### Community 101 - "Systemd Test ESLint Config"
Cohesion: 0.33
Nodes (5): env, mocha, rules, func-names, prefer-arrow-callback

### Community 102 - "Yarn Process Manager"
Cohesion: 0.33
Nodes (4): ProcessError, execa, {Observable}, {ProcessError}

### Community 103 - "Ghost User Detection"
Cohesion: 0.40
Nodes (5): execa, fs, getGhostUid(), os, shouldUseGhostUser()

### Community 104 - "npm Scripts"
Cohesion: 0.33
Nodes (6): scripts, coverage, lint, posttest, ship, test

### Community 105 - "Test ESLint Config"
Cohesion: 0.33
Nodes (5): env, mocha, rules, func-names, prefer-arrow-callback

### Community 106 - "Config Command Tests"
Cohesion: 0.40
Nodes (5): Config, {expect}, fake(), proxyquire, sinon

### Community 107 - "Logged-In Ghost User Tests"
Cohesion: 0.33
Nodes (5): errors, fs, ghostUser, loggedInGhostUser, sinon

### Community 108 - "Node Version Check Tests"
Cohesion: 0.33
Nodes (5): errors, path, proxyquire, sinon, {stripVTControlCharacters: stripAnsi}

### Community 109 - "Config Validation Tests"
Cohesion: 0.33
Nodes (5): advancedOpts, check, errors, {setupTestFolder, cleanupTestFolders}, sinon

### Community 110 - "Run Command Tests"
Cohesion: 0.33
Nodes (5): errors, EventEmitter, {getReadableStream}, proxyquire, sinon

### Community 111 - "Extension Base Tests"
Cohesion: 0.33
Nodes (5): fs, os, path, proxyquire, sinon

### Community 112 - "Migrator Tests"
Cohesion: 0.33
Nodes (5): configStub, errors, {expect}, proxyquire, sinon

### Community 113 - "Ghost User Detection Tests"
Cohesion: 0.33
Nodes (5): execa, fs, ghostUser, os, sinon

### Community 114 - "Log Command"
Cohesion: 0.40
Nodes (3): Command, LogCommand, TODO: fallback to process manager log retrieval?

### Community 116 - "Instance Config Model"
Cohesion: 0.40
Nodes (4): Config, fs, os, path

### Community 117 - "Repo File Layout"
Cohesion: 0.40
Nodes (5): files, bin, extensions, lib, yarn.lock

### Community 118 - "Directory Check Tests"
Cohesion: 0.40
Nodes (4): errors, fs, proxyquire, sinon

### Community 119 - "Folder Permission Tests"
Cohesion: 0.40
Nodes (4): errors, fs, proxyquire, sinon

### Community 120 - "Export Command Tests"
Cohesion: 0.40
Nodes (4): {expect}, proxyquire, sinon, {SystemError}

### Community 121 - "Import Command Tests"
Cohesion: 0.40
Nodes (4): {expect}, proxyquire, sinon, {SystemError}

### Community 122 - "Stop Command Tests"
Cohesion: 0.40
Nodes (4): proxyquire, sinon, StopCommand, {SystemError}

### Community 124 - "Config Subcommand Tests"
Cohesion: 0.50
Nodes (4): {expect}, fake(), proxyquire, sinon

### Community 125 - "Linux Process Manager Tests"
Cohesion: 0.40
Nodes (3): Promise, proxyquire, sinon

### Community 136 - "NYC Coverage Config"
Cohesion: 0.50
Nodes (4): nyc, exclude, **/*-spec.js, test

### Community 137 - "Check-Update Tests"
Cohesion: 0.50
Nodes (3): {expect}, proxyquire, sinon

### Community 138 - "Doctor Command Index Tests"
Cohesion: 0.50
Nodes (3): {expect}, proxyquire, sinon

### Community 139 - "Migrate Command Tests"
Cohesion: 0.67
Nodes (3): build(), proxyquire, sinon

### Community 140 - "Version Command Tests"
Cohesion: 0.50
Nodes (3): proxyquire, sinon, {stripVTControlCharacters: stripAnsi}

### Community 141 - "Dir-Is-Empty Tests"
Cohesion: 0.67
Nodes (3): {expect}, proxy(), proxyquire

### Community 142 - "Extension Discovery Tests"
Cohesion: 0.50
Nodes (3): localExtensions, proxyquire, sinon

### Community 146 - "Package Keywords"
Cohesion: 0.67
Nodes (3): ghost, keywords, cli

### Community 147 - "Package Repository Metadata"
Cohesion: 0.67
Nodes (3): repository, type, url

## Knowledge Gaps
- **851 isolated node(s):** `ghost`, `plugin:ghost/node`, `ecmaVersion`, `off`, `Promise` (+846 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **66 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `dependencies` connect `Root Package Dependencies` to `CLI Package Manifest`, `boxen dependency`, `chalk dependency`, `cli-table3 dependency`, `debug dependency`, `decompress dependency`, `execa dependency`, `find-plugins dependency`, `fkill dependency`, `form-data dependency`, `generate-password dependency`, `global-modules dependency`, `got dependency`, `https-proxy-agent dependency`, `inquirer dependency`, `jsonwebtoken dependency`, `latest-version dependency`, `listr dependency`, `lodash dependency`, `moment dependency`, `mysql2 dependency`, `ora dependency`, `package-json dependency`, `path-is-root dependency`, `portfinder dependency`, `prettyjson dependency`, `proxy-from-env dependency`, `read-last-lines dependency`, `replace-in-file dependency`, `rxjs dependency`, `semver dependency`, `shasum dependency`, `stat-mode dependency`, `symlink-or-copy dependency`, `systeminformation dependency`, `tail dependency`, `tough-cookie dependency`, `@tryghost/zip dependency`, `validator dependency`, `which dependency`, `yargs dependency`, `yarn dependency`?**
  _High betweenness centrality (0.054) - this node is a cross-community bridge._
- **Why does `Instance` connect `Stop Command` to `Instance Config Model`?**
  _High betweenness centrality (0.035) - this node is a cross-community bridge._
- **What connects `ghost`, `plugin:ghost/node`, `ecmaVersion` to the rest of the system?**
  _851 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `API Auth Strategies` be split into smaller, more focused modules?**
  _Cohesion score 0.07346938775510205 - nodes in this community are weakly interconnected._
- **Should `Agent Guide & Test Deps` be split into smaller, more focused modules?**
  _Cohesion score 0.061979648473635525 - nodes in this community are weakly interconnected._
- **Should `UID/Systemd Extension Utils` be split into smaller, more focused modules?**
  _Cohesion score 0.05609756097560976 - nodes in this community are weakly interconnected._
- **Should `UI Renderer Base` be split into smaller, more focused modules?**
  _Cohesion score 0.08961593172119488 - nodes in this community are weakly interconnected._