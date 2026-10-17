# NaturalPass corrections

This repository takes reports about values on [naturalpass.org](https://naturalpass.org).
It holds no code and no data.

Found a value that looks wrong, out of date or unclear? Open the value's source panel on the
site and choose **Report a problem with this value**. That opens an issue here with the state,
metric ID, period, source and data version already filled in. You only need to say what's wrong
and where you saw the right number.

You can also [open a blank report](https://github.com/NaturalPass/corrections/issues/new?template=correction.yml).

## What happens next

We check the report against the source document. If the value is wrong, we fix it in a new data
version and list the fix in the changelog on the [data page](https://naturalpass.org/data/).
Old versions never change, so anything you cited keeps pointing at the same numbers.
We close the issue with the version that carries the fix, or with the reason we kept the value.
