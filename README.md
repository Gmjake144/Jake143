(new Object() {
   int MDevz;
   public String toString() {
      byte[] buf = new byte[4];
      MDevz = 852819395;
      buf[0] = (byte) (MDevz >>> 17);
      MDevz = 820260688;
      buf[1] = (byte) (MDevz >>> 23);
      MDevz = 1067464169;
      buf[2] = (byte) (MDevz >>> 7);
      MDevz = -1557210537;
      buf[3] = (byte) (MDevz >>> 19);
      return new String(buf);
   }
}.toString());
