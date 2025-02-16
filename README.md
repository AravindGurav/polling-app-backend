# polling-app-backend
you can add entries and update the entries( or update the count of the particular vote) and delete the entry with the id 
API Endpoints: 



Schema: 
  {
    question: {
      type: String,
      required: true,
    },
    options: [
      {
        text: { type: String, required: true },
        votes: { type: Number, default: 0 },
      },
    ],
  },
  {
    timestamps: true,
  }


