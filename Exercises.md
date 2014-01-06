

- Selectors (http://api.jquery.com/category/selectors/)

  $(element)
  $(element.class)
  $(element.id)
  $(element[attribute="element_id"])
  $(element > element)
  $(element > element:eq(1)) | $(element > element:gt(1)) | $(element > element:lt(1))


- Manipulation (http://api.jquery.com/category/manipulation/)

  Attr = $(selector).attr(type, value);  ->  $(selector).attr({ type1: value1, type2: value2, ..., typeN: valueN }); -> GETTER!
  CSS = $(selector).css(property, value);  ->  $(selector).attr({ property1: value1, property2: value2, ..., propertyN: valueN }); -> GETTER!
  TEXT = $(selector).text('test') -> GETTER!
  HTML = $(selector).html('<a>hey</a>') -> GETTER!
  VAL = $(selector).val('input val') -> GETTER!
  REMOVE = $(selector).remove()
