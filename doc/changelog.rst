ChangeLog
=========

0.4.4 (29/05/2012)
------------------

*Bugfix:*

    * Serialize unicode of :attr:`xworkflows.State.title` in south ORM freezing.

0.4.3 (29/05/2012)
------------------

*Bugfix:*

    * Include migrations in package

0.4.2 (29/05/2012)
------------------

*Bugfix:*

    * Fix log=False/save=False when calling transitions

0.4.1 (29/05/2012)
------------------

*Bugfix:*

    * Avoid circular import issues when resolving :attr:`~django_xworkflows.models.Workflow.log_model`
      to a :class:`~django.db.models.Model`
    * Log source and target state names in :class:`~django_xworkflows.models.TransitionLog`

0.4.0 (29/04/2012)
------------------

*New:*

    * Improve south support (
    * Run transition implementations in a database transaction

0.3.1 (15/04/2012)
------------------

*New:*

    * Introduce :class:`~django_xworkflows.models.StateField` for adding a :class:`~django_xworkflows.models.Workflow`
      to a model
    * Adapt to xworkflows-0.3.0


.. vim:et:ts=4:sw=4:tw=79:ft=rst: