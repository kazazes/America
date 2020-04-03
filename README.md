# America

## Changelog
### America 1.4, 2001-2020
### America 1.3, 1964-2001
### America 1.2, 1939-1964
### America 1.1, 1865-1939
#### Added

  - New Deal (thanks @realFDR)
    - Significant refactoring of internal infrastructure
    - Added prop validation to Banker class
    - Adds Union itterable, a collection of Worker objects which interacts with Monopoly and other Company types
    - Added HousingAuthority (WIP), an observer intended to add Citizen objects to Housing 
    - SocialSecruityFramework, which allows Worker to make an async call to Market via Government, passing Currency as a param. Market returns Currency.

#### Fixed

- 13th Amendment, addresses #1 (WIP)
Changed
- Reunified to monorepo  after microservices killed ~1mm Americans (#1)
##### Known Bugs
- #2, see below
- #1 fix needs to be merged with preamble of Constitution
- HousingAuthority is creating Housing objects which fail tests
Help Wanted
- 13th Amendment not doing all  we intended

### America 1.0, 1776-1861
#### Added

- [Declaration of Independence](LICENSE.md) (thanks @jadams76 @4eyedfranklin, et al.)
- Sovereignty
Changed
- Dynamic east-west storage expansion parameters adjusted for increased aggression
- Refactored internal data structures
Known Bugs
- Economy entirely dependent on slave labor, hot fix in testing (#1)
- Westward expansion directly causing unneeded slaughter of native populations (#2)

