# Changelog

## [0.6.0] - 22.03.2022
### Added
- suport VS2022
- support amd64
- xunit Projekttemplate addet `PlatformTag` for Linux and macOS

### Change
- Remove xBehave templates
- Default target moniker is now `net6.0`
- xunit class has no ctor by default. Use `xUnitCtor` template to create it if needed

## [0.5.0] - internal
### Added
- VS 2019 Project Dialog Tag discovery

## [0.4.1] - 06.02.2019
### Fixed
- Release note link in Extension Manager
- XUnit Projekt template Unit test file wil now copied

## [0.4.0] - 24.01.2019
### Added
**Common:**
- Project restart after technical limitation in previes release https://marketplace.visualstudio.com/items?itemName=bqstony.csharpitemtemplates1
- support VS2017 / (preview) VS2019
- support .Net standard projects

**CSharp Item Templates:**
- public class
- public enum
- public interface
- xUnit test

**CSharp Project Templates:**
- xUnit Project

**CSharp code snippet:**
- xUnit fact method -> 'xUnitFact'
- xUnit theory method -> 'xUnitTheory'
- xUnit ctor with ITestOutputHelper -> 'xUnitCtor'
- xBehave scenario method -> 'xBehaveScenario'
- xBehave background method -> 'xBehaveBackground'
- xBehave step -> 'xBehaveStep' or 'xBehaveStepCompact'
