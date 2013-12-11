# -*- ruby -*-

LIB_DIR = 'lib'
BASE_DIR = '..'
ADA_LIB = 'Adafruit-Motor-Shield-library'
AFMOTOR_LIB = File.join(LIB_DIR, "AFMotor")

directory AFMOTOR_LIB do
  cp_r File.join(BASE_DIR, ADA_LIB), LIB_DIR
  mv File.join(LIB_DIR, ADA_LIB), AFMOTOR_LIB
end

task :default => AFMOTOR_LIB

