When printf processes its arguments, it startsprinting the characters it ﬁnds in the ﬁrst argument,one by one. When it ﬁnds a percent it knows it has a format speciﬁcation. It goes to the next ar-gument and uses its value, printing it according tothat format speciﬁcation. It then returns to printinga character at a time (from the ﬁrst argument).It is okay to include more than one format speci-ﬁcation in the printf string
