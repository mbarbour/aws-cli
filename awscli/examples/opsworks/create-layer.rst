**To create a layer**

The following ``create-layer`` command creates a PHP App Server layer named MyPHPLayer.::

  aws opsworks create-layer --stack-id f6673d70-32e6-4425-8999-265dd002fec7 --type php-app --name MyPHPLayer --shortname myphplayer

**Note**: OpsWorks CLI commands should set the region to us-east-1, regardless of the stack's location.

Output::

  {
    "LayerId": "0b212672-6b4b-40e4-8a34-5a943cf2e07a"
  }

For more information, see `How to Create a Layer`_ in the *OpsWorks User Guide*.

.. _`How to Create a Layer`: http://docs.aws.amazon.com/opsworks/latest/userguide/workinglayers-basics-create.html
