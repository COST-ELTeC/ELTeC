## Release numbering scheme

The ELTeC collections receive version numbers following a semantic versioning scheme with three digits, following the model v1.2.3. 

* The first digit represents major milestones
* The second digit represents substantial advances towards a major milestone, such as adding some new texts
* The second digit represents minor fixes, such as improving the encoding of some files or adding metadata

**First digit: major milestones**

* v1.0.0 when a given collection reaches 100 novels encoded at either level 0 or level 1 (even if the corpus composition criteria are not yet 100% respected)
* v2.0.0 when a given collection reaches 100 novels encoded also at level 2

**Second digit: substantial advances**

We set the second digit as roughly indicating the proportion of work (between 0 and 10, for 0 to 100%) already achieved towards the next milestone

Whenever there is a substantial advance, this digit can be incremented either by one integer (default case) or by several integers (if a big step has been taken)

**Third digit: minor fixes**

We set the third digit to zero by default. If some fixes are applied to a collection that do not reach the level of a substantial advance, either no new release is made, or if a new release is made, it will be made with an increment of one integer on the third digit.

## Umbrella release

The semantic versioning scheme described above is also used for the umbrella release. 

**First digit: major milestones**

* v1.0.0 when we have 10 substantial collections (10 collections at v0.5.0 or higher)
* v2.0.0 when we have 10 complete collections (10 collections at v1.0.0)
* v3.0.0 when we have 10 substantial annotated collections (10 collections at v1.5.0 or higher) (problematic: what if we have collections that are smaller than 100 novels but have been annotated?)
* v4.0.0 when we have 10 complete annotated collections (10 collections at v2.0.0 or higher)
* v5.0.0 when we have at least 15 complete annotated collections (15 collections at v.2.0.0 or higher)

**Second digit: progress towards milestones** 

We set the second digit as roughly indicating the proportion of work (between 0 and 10, for 0 to 100%) already achieved towards the next milestone.

**Third digit: minor fixes** 

This is used only for minor adjustments to the repository.
