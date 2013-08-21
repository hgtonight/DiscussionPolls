## Project Summary ##

We, the [Vanilla Forums](http://www.vanillaforums.org/discussions) community, want to offer a compelling poll plugin. It will attach to discussions, respect permission, and have a compelling UX.

## Formal Requirements ##

### Initial Release ###
1. ~~Plugin will be compatible with Vanilla 2.0.x and Vanilla 2.1b1~~
2. Plugin will be released under an approved Open Source License
3. ~~Plugin will be documented~~
    1. ~~Each **non-trivial** method will be documented~~
        1. ~~Intent of method will be described~~
        2. ~~Parameters will be described~~
		3. ~~Return will be described~~
    2. A readme will be provided
	    1. ~~Installation will be described~~
        2. ~~Configuration will be described~~
        3. ~~Common issues will be described~~
4. ~~Poll creation and deletion will respect permissions~~
    1. ~~Can be set per role~~
    2. ~~Original author can delete poll without needing deletion permissions~~
5. ~~Each Poll will comprise of 1 or more Poll Questions~~
6. ~~Each Poll Question will comprise of 2 or more Poll Answers~~
7. ~~Each User will be able to Select only one Poll Answer per Poll Question~~
8. ~~Each User must answer every Poll Question to submit a Poll successfully~~
9. ~~Each User must be logged in to submit a Poll~~
10. ~~Polls will be created with standard UX~~
    1. ~~Via checkbox at Discussion creation~~
    2. ~~Via poll link after Discussion creation~~
    3. ~~Creation form will be revealed inline~~
11. ~~Each Discussion will only have 0 or 1 attached Poll~~
    1. ~~Poll will be displayed in the Discussion body to which it is attached~~
12. ~~Poll will be deleted if attached Discussion is removed~~
13. ~~Poll will be disabled if attached Discussion is closed~~
14. ~~Results will be shown after successful voting~~
15. ~~Results will be shown after Show Results toggle~~
    1. ~~Show Results toggle will be displayed per a configurable setting~~
16. ~~Results will provide a clean presentation~~
    1. ~~Total Votes will be displayed~~
    2. ~~Each Poll Question will display each Poll Answer~~
        1. ~~Colored bars will be displayed next to each Poll Answer~~
            1. ~~Bar width will be representative of the percentage of votes indicating the Poll Answer~~
        2. ~~Percentage of votes indicating the Poll Answer will be displayed~~
17. ~~Default styling will work in default theme~~

### Subsequent Releases ###
1. Polls will be able to be closed independently of discussion
1. Poll will automatically expire after 7 days
    1. Expiration will be a configurable setting
2. Poll editing will respect permissions
    1. Can be set per role
    2. Original author can edit poll without needing editing permissions
3. Poll editing will be disabled upon first successful Poll submission
4. Results will offer compact mode
    1. Poll Answers with 0 votes will not be displayed
	2. Total Votes will not be displayed
5. Each Poll will be attached to 0 or more Categories
    1. Poll will be displayed in Panel
6. Polls will have an administration screen

## Steps to Proceed ##
- ~~Setup development environment~~
- ~~Finalize requirements~~
- ~~Analyze differences in 2.1b1 and 2.0.x event hooks for Discussion and Post controllers~~
- ~~Determine necessary event hooks~~
    - ~~Place placeholder comments describing functionality required~~
- ~~Determine Poll model~~
- ~~Determine optimal views~~
- ~~Implement apparent methods~~
- ~~Test functionality~~
- ~~Flesh out descriptions of functionality~~
- Double check documentation
- Release

## Sponsors ##
50sQuiff, whu606, x00, hgtonight
