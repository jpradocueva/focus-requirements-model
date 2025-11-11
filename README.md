# focus-requirements-model
Repository dedicated to FOCUS Requirements Model
### See deltas side-by-side
```bash
git diff --no-index --color-words availabilityzone_v1-2.md availabilityzone_v1-3.md
```

### Running code --diff in VS code

#### Step 1: Install 'code' command in PATH
1. Open VS Code
2. Press `Cmd + Shift + P` (Mac) or `Ctrl + Shift + P` (Windows/Linux) to open the Command Palette.
3. Type 

```bash
shell command
```
 and select `Shell Command: Install 'code' command in PATH` from the dropdown.

Now, you can use `code` directly from any terminal window.

#### Step 2: Use `code --diff`
1. Go to View --> terminal
2. Navigate to the directory where your files are located.

For example
```bash
cd specification/dataset/columns 
```

#### Step 3: Run the diff command
Run: (for example)

```bash
code --diff availabilityzone_v1-2.md availabilityzone_v1-3.md                                            
```

### Contract & Usage deltas
This list of terminal commands facilitate to run diffs side-by-side in VS code for different columns for versions 1.2 and 1.3 of the FOCUS Requirements Model.

code --diff availabilityzone_v1-2.md availabilityzone_v1-3.md
code --diff billedcost_v1-2.md billedcost_v1_3.md
code --diff billingaccountid_v1-2.md billingaccountid_v1_3.md
code --diff billingaccountname_v1-2.md billingaccountname_v1_3.md
code --diff billingaccounttype_v1-2.md billingaccounttype_v1_3.md
code --diff billingcurrency_v1-2.md billingcurrency_v1_3.md
code --diff billingperiodend_v1-2.md billingperiodend_v1_3.md
code --diff billingperiodstart_v1-2.md billingperiodstart_v1_3.md
code --diff capacityreservationid_v1-2.md capacityreservationid_v1_3.md
code --diff capacityreservationstatus_v1-2.md capacityreservationstatus_v1_3.md
code --diff chargecategory_v1-2.md chargecategory_v1_3.md
code --diff chargeclass_v1-2md chargeclass_v1_3.md
code --diff chargedescription_v1-2.md chargedescription_v1_3.md
code --diff chargefrequency_v1-2.md chargefrequency_v1_3.md
code --diff chargeperiodend_v1-2.md chargeperiodend_v1_3.md
code --diff chargeperiodstart_v1-2.md chargeperiodstart_v1_3.md
code --diff commitmentdiscountcategory_v1-2.md commitmentdiscountcategory_v1_3.md
code --diff commitmentdiscountid_v1-2.md commitmentdiscountid_v1_3.md
code --diff commitmentdiscountname_v1-2.md commitmentdiscountname_v1_3.md
code --diff commitmentdiscountquantity_v1-2.md commitmentdiscountquantity_v1_3.md
code --diff commitmentdiscountstatus_v1-2.md commitmentdiscountstatus_v1_3.md
code --diff commitmentdiscounttype_v1-2.md commitmentdiscounttype_v1_3.md
code --diff commitmentdiscountunit_v1-2.md commitmentdiscountunit_v1_3.md
code --diff consumedquantity_v1-2.md consumedquantity_v1_3.md
code --diff consumedunit_v1-2.md consumedunit_v1_3.md
code --diff contractedcost_v1-2.md contractedcost_v1_3.md
code --diff contractedunitprice_v1-2.md contractedunitprice_v1_3.md
code --diff effectivecost_v1-2.md effectivecost_v1_3.md
code --diff invoiceid_v1-2.md invoiceid_v1_3.md
code --diff invoiceissuer_v1-2.md invoiceissuername_v1_3
code --diff listcost._v1-2md listcost_v1_3.md
code --diff listunitprice_v1-2.md listunitprice_v1_3.md
code --diff pricingcategory_v1-2.md pricingcategory_v1_3.md
code --diff pricingcurrency_v1-2.md pricingcurrency_v1_3.md
code --diff pricingcurrencycontractedunitprice_v1-2.md pricingcurrencycontractedunitprice_v1_3.md
code --diff pricingcurrencyeffectivecost_v1-2.md pricingcurrencyeffectivecost_v1_3.md
code --diff pricingcurrencylistunitprice_v1-2.md pricingcurrencylistunitprice_v1_3.md
code --diff pricingquantity_v1-2.md pricingquantity_v1_3.md
code --diff pricingunit_v1-2.md pricingunit_v1_3.md
code --diff regionid_v1-2.md regionid_v1_3.md
code --diff regionname_v1-2.md regionname_v1_3.md
code --diff resourceid_v1-2.md resourceid_v1_3.md
code --diff resourcename_v1-2.md resourcename_v1_3.md
code --diff resourcetype_v1-2.md resourcetype_v1_3.md
code --diff servicecategory_v1-2.md servicecategory_v1_3.md
code --diff servicename_v1-2.md servicename_v1_3.md
code --diff servicesubcategory_v1-2.md servicesubcategory_v1_3.md
code --diff skuid_v1-2.md skuid_v1_3.md
code --diff skumeter_v1-2.md skumeter_v1_3.md
code --diff skupricedetails_v1-2.md skupricedetails_v1_3.md
code --diff skupriceid_v1-2.md skupriceid_v1_3.md
code --diff subaccountid_v1-2.md subaccountid_v1_3.md
code --diff subaccountname_v1-2.md subaccountname_v1_3.md
code --diff subaccounttype_v1-2.md subaccounttype_v1_3.md
code --diff tags_v1-2.md tags_v1_3.md
