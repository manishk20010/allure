# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: AgentRegistration.spec.ts >> Agent Registration
- Location: tests\AgentRegistration.spec.ts:6:5

# Error details

```
Test timeout of 30000ms exceeded.
```

```
Error: locator.check: Test timeout of 30000ms exceeded.
Call log:
  - waiting for getByTitle('Select Record')

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e2]:
    - generic [ref=e4]:
      - list [ref=e6]:
        - listitem [ref=e7]:
          - link "Maryland.gov" [ref=e8] [cursor=pointer]:
            - /url: http://www.maryland.gov/Pages/default.aspx
      - generic [ref=e9]:
        - generic "Logo of Maryland Department of Labor , Licensing and Regulation" [ref=e10]
        - list [ref=e12]:
          - listitem [ref=e13]:
            - button "Facebook" [ref=e14] [cursor=pointer]
          - listitem [ref=e15]:
            - button "Twitter" [ref=e16] [cursor=pointer]
          - listitem [ref=e17]:
            - button "Youtube" [ref=e18] [cursor=pointer]
          - listitem [ref=e19]:
            - button "All" [ref=e20] [cursor=pointer]
      - generic [ref=e21]:
        - generic [ref=e22]: Welcome to the Agent Portal
        - list
    - generic [ref=e25]:
      - generic [ref=e26]: Fields marked with an * are required
      - generic [ref=e28]:
        - generic [active] [ref=e29]: "[ Errors found. Record not saved. ]"
        - list [ref=e31]:
          - listitem [ref=e32]: Business Legal Name is required
        - generic:
          - generic [ref=e34]:
            - list [ref=e35]:
              - listitem [ref=e36]:
                - generic "Step Progress-1" [ref=e37]: Login Information
              - listitem [ref=e38]:
                - generic "Step Progress-2" [ref=e39]: Contact Information
              - listitem [ref=e40]:
                - generic "Step Progress-3" [ref=e41]: Business Information
              - listitem [ref=e42]:
                - generic "Confirmation" [ref=e43]
              - listitem [ref=e44]:
                - generic "TPA Account Number" [ref=e45]
            - generic:
              - list
          - generic [ref=e46]:
            - list [ref=e47]:
              - listitem [ref=e48]:
                - link "Login Information" [ref=e49]:
                  - /url: "#wzsStepLoginInfo"
                  - generic "Login Information" [ref=e50]
              - listitem [ref=e51]:
                - link "Contact Information" [ref=e52]:
                  - /url: "#wzsStepContactInfo"
                  - generic "Contact Information" [ref=e53]
              - listitem [ref=e54]:
                - link "Business Information" [ref=e55]:
                  - /url: "#wzsStepBusinessInfo"
                  - generic "Business Information" [ref=e56]
              - listitem
              - listitem
              - listitem
            - generic [ref=e58]:
              - table "ADA" [ref=e60]:
                - rowgroup [ref=e61]:
                  - row [ref=e62]:
                    - cell [ref=e63]
                    - cell [ref=e64]
                    - cell [ref=e65]
                    - cell [ref=e66]
              - heading "Business Information" [level=2] [ref=e67]
              - table "ADA" [ref=e68]:
                - rowgroup [ref=e69]:
                  - row "Enter information regarding your business. The business Email address is the address that will be used for all communications." [ref=e70]:
                    - cell "Enter information regarding your business. The business Email address is the address that will be used for all communications." [ref=e71]
                  - row [ref=e72]:
                    - cell [ref=e73]
                    - cell [ref=e74]
                  - 'row "Business Legal Name: * Smith45" [ref=e75]':
                    - cell "Business Legal Name:" [ref=e76]
                    - cell "* Smith45" [ref=e77]:
                      - generic [ref=e78]: "*"
                      - textbox "Business Legal Name:" [ref=e79]: Smith45
                  - row "Business Trade Name or DBA Name:" [ref=e80]:
                    - cell "Business Trade Name or DBA Name:" [ref=e81]:
                      - button "Business Trade Name or DBA Name:" [ref=e82] [cursor=pointer]
                    - cell [ref=e83]:
                      - textbox "Business Trade Name or DBA Name:" [ref=e84]
                  - 'row "Business Email Address: * hello@mail.com" [ref=e85]':
                    - cell "Business Email Address:" [ref=e86]
                    - cell "* hello@mail.com" [ref=e87]:
                      - generic [ref=e88]: "*"
                      - textbox "Business Email Address:" [ref=e89]: hello@mail.com
                  - 'row "Confirm Business Email Address: * hello@mail.com" [ref=e90]':
                    - cell "Confirm Business Email Address:" [ref=e91]
                    - cell "* hello@mail.com" [ref=e92]:
                      - generic [ref=e93]: "*"
                      - textbox "Confirm Business Email Address:" [ref=e94]: hello@mail.com
                  - 'row "FEIN: * 21-5634859" [ref=e95]':
                    - cell "FEIN:" [ref=e96]
                    - cell "* 21-5634859" [ref=e97]:
                      - generic [ref=e98]: "*"
                      - textbox "FEIN:" [ref=e99]: 21-5634859
                  - 'row "Country: * UNITED STATES OF AMERICA (USA)" [ref=e100]':
                    - cell "Country:" [ref=e101]
                    - cell "* UNITED STATES OF AMERICA (USA)" [ref=e102]:
                      - generic [ref=e103]: "*"
                      - combobox "Country:" [ref=e104]:
                        - option "UNITED STATES OF AMERICA (USA)" [selected]
                        - option "CANADA"
                  - row "Attention:" [ref=e105]:
                    - cell "Attention:" [ref=e106]
                    - cell [ref=e107]:
                      - textbox "Attention:" [ref=e108]
                  - 'row "Address 1: * This is new Address by Automation" [ref=e109]':
                    - cell "Address 1:" [ref=e110]
                    - cell "* This is new Address by Automation" [ref=e111]:
                      - generic [ref=e112]: "*"
                      - textbox "Address 1:" [ref=e113]: This is new Address by Automation
                  - row "Address 2:" [ref=e114]:
                    - cell "Address 2:" [ref=e115]
                    - cell [ref=e116]:
                      - textbox "Address 2:" [ref=e117]
                  - 'row "City: * MD" [ref=e118]':
                    - cell "City:" [ref=e119]
                    - cell "* MD" [ref=e120]:
                      - generic [ref=e121]: "*"
                      - textbox "City:" [ref=e122]: MD
                  - 'row "State: * ALABAMA" [ref=e123]':
                    - cell "State:" [ref=e124]
                    - cell "* ALABAMA" [ref=e125]:
                      - generic [ref=e126]: "*"
                      - combobox "State:" [ref=e127]:
                        - option
                        - option "ALABAMA" [selected]
                        - option "ALASKA"
                        - option "AMERICAN SAMOA"
                        - option "ARIZONA"
                        - option "ARKANSAS"
                        - option "ARMED FORCES AFRICA, CANADA, EUROPE AND MIDDLE EAST"
                        - option "ARMED FORCES AMERICAS (EXCEPT CANADA)"
                        - option "ARMED FORCES PACIFIC"
                        - option "CALIFORNIA"
                        - option "COLORADO"
                        - option "CONNECTICUT"
                        - option "DELAWARE"
                        - option "DISTRICT OF COLUMBIA"
                        - option "FLORIDA"
                        - option "GEORGIA"
                        - option "GUAM"
                        - option "HAWAII"
                        - option "IDAHO"
                        - option "ILLINOIS"
                        - option "INDIANA"
                        - option "IOWA"
                        - option "KANSAS"
                        - option "KENTUCKY"
                        - option "LOUISIANA"
                        - option "MAINE"
                        - option "MARYLAND"
                        - option "MASSACHUSETTS"
                        - option "MICHIGAN"
                        - option "MINNESOTA"
                        - option "MISSISSIPPI"
                        - option "MISSOURI"
                        - option "MONTANA"
                        - option "NEBRASKA"
                        - option "NEVADA"
                        - option "NEW HAMPSHIRE"
                        - option "NEW JERSEY"
                        - option "NEW MEXICO"
                        - option "NEW YORK"
                        - option "NORTH CAROLINA"
                        - option "NORTH DAKOTA"
                        - option "NORTHERN MARIANA ISLANDS"
                        - option "OHIO"
                        - option "OKLAHOMA"
                        - option "OREGON"
                        - option "PENNSYLVANIA"
                        - option "PUERTO RICO"
                        - option "RHODE ISLAND"
                        - option "SOUTH CAROLINA"
                        - option "SOUTH DAKOTA"
                        - option "TENNESSEE"
                        - option "TEXAS"
                        - option "U.S. VIRGIN ISLANDS"
                        - option "UTAH"
                        - option "VERMONT"
                        - option "VIRGINIA"
                        - option "WASHINGTON"
                        - option "WEST VIRGINIA"
                        - option "WISCONSIN"
                        - option "WYOMING"
                  - 'row "Zip/Postal Code: * 12345 -" [ref=e128]':
                    - cell "Zip/Postal Code:" [ref=e129]
                    - cell "* 12345 -" [ref=e130]:
                      - generic [ref=e131]: "*"
                      - textbox "Zip/Postal Code:" [ref=e132]: "12345"
                      - text: "-"
                      - textbox "Zip" [ref=e133]
                  - 'row "County: BALDWIN" [ref=e134]':
                    - cell "County:" [ref=e135]
                    - cell "BALDWIN" [ref=e136]:
                      - combobox "County:" [ref=e137]:
                        - option
                        - option "AUTAUGA"
                        - option "BALDWIN" [selected]
                        - option "BARBOUR"
                        - option "BIBB"
                        - option "BLOUNT"
                        - option "BULLOCK"
                        - option "BUTLER"
                        - option "CALHOUN"
                        - option "CHAMBERS"
                        - option "CHEROKEE"
                        - option "CHILTON"
                        - option "CHOCTAW"
                        - option "CLARKE"
                        - option "CLAY"
                        - option "CLEBURNE"
                        - option "COFFEE"
                        - option "COLBERT"
                        - option "CONECUH"
                        - option "COOSA"
                        - option "COVINGTON"
                        - option "CRENSHAW"
                        - option "CULLMAN"
                        - option "DALE"
                        - option "DALLAS"
                        - option "DE KALB"
                        - option "ELMORE"
                        - option "ESCAMBIA"
                        - option "ETOWAH"
                        - option "FAYETTE"
                        - option "FRANKLIN"
                        - option "GENEVA"
                        - option "GREENE"
                        - option "HALE"
                        - option "HENRY"
                        - option "HOUSTON"
                        - option "JACKSON"
                        - option "JEFFERSON"
                        - option "LAMAR"
                        - option "LAUDERDALE"
                        - option "LAWRENCE"
                        - option "LEE"
                        - option "LIMESTONE"
                        - option "LOWNDES"
                        - option "MACON"
                        - option "MADISON"
                        - option "MARENGO"
                        - option "MARION"
                        - option "MARSHALL"
                        - option "MOBILE"
                        - option "MONROE"
                        - option "MONTGOMERY"
                        - option "MORGAN"
                        - option "PERRY"
                        - option "PICKENS"
                        - option "PIKE"
                        - option "RANDOLPH"
                        - option "RUSSELL"
                        - option "SAINT CLAIR"
                        - option "SHELBY"
                        - option "SUMTER"
                        - option "TALLADEGA"
                        - option "TALLAPOOSA"
                        - option "TUSCALOOSA"
                        - option "WALKER"
                        - option "WASHINGTON"
                        - option "WILCOX"
                        - option "WINSTON"
                  - 'row "Business Telephone Number: * (213) 666-5898 Ext" [ref=e138]':
                    - cell "Business Telephone Number:" [ref=e139]
                    - cell "* (213) 666-5898 Ext" [ref=e140]:
                      - generic [ref=e141]: "*"
                      - textbox "Business Telephone Number:" [ref=e142]: (213) 666-5898
                      - text: Ext
                      - textbox "Ext" [ref=e143]
                  - 'row "Receive Benefit Charge Statements electronically; do not mail : * Yes No" [ref=e144]':
                    - cell "Receive Benefit Charge Statements electronically; do not mail :" [ref=e145]
                    - cell "* Yes No" [ref=e146]:
                      - generic [ref=e147]: "*"
                      - generic [ref=e148]:
                        - generic [ref=e149]:
                          - radio "Yes" [checked] [ref=e150]
                          - text: "Yes"
                        - generic [ref=e152]:
                          - radio "No" [ref=e153]
                          - text: "No"
                  - 'row "Receive Tax Rate Notices electronically; do not mail : * Yes No" [ref=e155]':
                    - cell "Receive Tax Rate Notices electronically; do not mail :" [ref=e156]
                    - cell "* Yes No" [ref=e157]:
                      - generic [ref=e158]: "*"
                      - generic [ref=e159]:
                        - generic [ref=e160]:
                          - radio "Yes" [checked] [ref=e161]
                          - text: "Yes"
                        - generic [ref=e163]:
                          - radio "No" [ref=e164]
                          - text: "No"
                  - row [ref=e166]:
                    - cell [ref=e167]
                  - row [ref=e168]:
                    - cell [ref=e169]
                  - row [ref=e170]:
                    - cell [ref=e171]
            - generic [ref=e172]:
              - link "Previous" [ref=e173] [cursor=pointer]:
                - /url: javascript:void(0)
              - link "Next" [ref=e174] [cursor=pointer]:
                - /url: javascript:void(0)
              - link "Finish" [ref=e175]:
                - /url: javascript:void(0)
    - generic [ref=e176]:
      - list [ref=e177]:
        - listitem [ref=e178]:
          - link "Contact Us" [ref=e179] [cursor=pointer]:
            - /url: "#"
        - listitem [ref=e180]:
          - link "Privacy" [ref=e181] [cursor=pointer]:
            - /url: "#"
        - listitem [ref=e182]:
          - link "Accessibility" [ref=e183] [cursor=pointer]:
            - /url: "#"
        - listitem [ref=e184]:
          - link "Posters" [ref=e185] [cursor=pointer]:
            - /url: "#"
        - listitem [ref=e186]:
          - link "MPIA" [ref=e187] [cursor=pointer]:
            - /url: "#"
        - listitem [ref=e188]:
          - link "Ayuda en espanol" [ref=e189] [cursor=pointer]:
            - /url: "#"
      - paragraph [ref=e190]: 100 S. Charles St., Tower 1, Suite 3100, Baltimore, MD 21201
  - log [ref=e192]
  - log [ref=e193]
  - log [ref=e194]
```

# Test source

```ts
  1  | import { Page, Locator } from "@playwright/test";
  2  | 
  3  | export class AddressOption {
  4  |      page:Page
  5  |      Next:Locator
  6  |      option:Locator
  7  | 
  8  |         constructor(page:Page){
  9  |             this.page=page
  10 | 
  11 |             this.option= page.getByTitle('Select Record')
  12 |             this.Next = page.getByRole('link',{name:'Next'})
  13 | 
  14 |         }
  15 |             async option1(){
  16 | 
> 17 |                 await this.option.check()
     |                                   ^ Error: locator.check: Test timeout of 30000ms exceeded.
  18 |             }
  19 | 
  20 |           async nextpagenavigate(){
  21 | 
  22 |                 await this.Next.click()
  23 |             }
  24 | 
  25 | 
  26 |         
  27 |     }
```