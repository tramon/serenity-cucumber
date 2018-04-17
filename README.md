This is a basic Serenity Cucumber Test Automation framework for Acceptance testing

For now:
- This framework works only on Windows
- This framework works only on Chrome v65

To run the test:
- Please put v.2.37 chromedriver.exe into drivers package inside the project
- Configure Gradle Runner: 'clean test aggregate'
- Or run from console: gradle clean test aggregate

Reports can be found in project here:
- Cucumber reports: \\serenitycucumber\build\reports\tests\test\index.html
- Serenity reports: \\serenitycucumber\target\site\serenity\index.html