CascadableBehavior
==================

CakePHP Behavior to merge records with same id from child database into parent database

WARNING: This behavior is not production ready.

Compatibility: CakePHP up to 2.4.7

This behavior does not actually "behave" automatically. The afterFind() callback method has been changed to doAfterFind() and must be called manually. This is because callbacks are not auto firing for associated models.
