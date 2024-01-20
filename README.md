# Fire-Detection-System
  A fire  detection system uses deep learning to process large amounts of data to identify and classify fire.
# Import necessary libraries
  import tensorflow as tf
  from tensorflow import keras
  from tensorflow.keras import layers
  from tensorflow.keras.preprocessing.image import ImageDataGenerator
  from tensorflow.keras.applications import MobileNetV2
  from tensorflow.keras.applications.mobilenet_v2 import preprocess_input
  from tensorflow.keras.models import Model
  from tensorflow.keras.optimizers import Adam
  import cv2         # Library for OpenCV
  import threading   # Library for threading -- which allows code to run in the backend
  import pygame   # Library for alarm sound
  import smtplib     # Library for email sending
  import urllib.request
  import urllib.error
  from email. message import EmailMessage
  import ssl
