Articles Data Structure

# Articles data

Articles **{**
* id,
* Text,
* UnitType,
* Status **[**
  * **{**
    * Status,
    * Effective,
    * Created**}****]**,

  Authors **[**
    **{**
      Name,
      DBO…**}****]**,
  Publication **[**
    **{**
      Publisher,
      PubDate**}****]**,
  Parents **[**
    Article_id**]**,
  Categories **[**
    Category_no**]**,
  Subjects **[**
      Subject_no**]**,
  References **[**
    **{**Some pre determined data structure like oxford**}****]****}**

# Tables structure

* tbl_Articles
    * id
    * text
    * unit_type

* tbl_ArticlesAuthours
    * article_id
    * authour_id
    * type

* tbl_Authours
    * id
    * name
    * dbo
    * …

* tbl_Statuses
    * status
    * article_id
    * effective
    * created

* tbl_ArticlesPublishers
    * article_id
    * publisher_id
    * publication_date

* tbl_Publishers
    * id
    * name
    * ...

* tbl_ArticlesParents
    * parent_id
    * child_id

* tbl_ArticlesCategories
    * article_id
    * Category_id

* tbl_Categories
    * id
    * name
    * parent_id ← can a category exist within multiple parent categories?

* tbl_ArticlesSubjects
    * article_id
    * subject_id

* tbl_Subjects
    * id
    * name
    * …

* tbl_ArticlesReferences
    * article_id
    * reference_id

* tbl_References
    * id
    * name
    * …
