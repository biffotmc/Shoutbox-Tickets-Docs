Usage
=====

.. _General Usage:

Opening a ticket
----------------

To open a ticket:
Go to the #open-a-ticket channel, and find the panel shown below

.. image:: D1E52B98-AF8D-4294-9871-FBBB0ADE3B64.jpeg
    :alt: Ticket Panel

Choose what type of ticket you would like to open and press the 
corresponding button.

Commands inside a ticket
------------------------

To add another person to your ticket you will need to ask the
staff member who is responding to your ticket to add the person 
using /add, you will need to provide the whole discord tag for
the staff member e.g. Clyde#0001.

To remove a person from your ticket it is the same process.

To reopen your ticket you can use the button in the ticket.

Closing a ticket
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

