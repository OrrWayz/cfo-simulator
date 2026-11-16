# The CFO Simulator: Ross Halloran

Practise asking a sceptical CFO for money, tonight, before you do it for real tomorrow.

Drop this folder into a Claude project and Claude becomes **Ross Halloran**, CFO of a mail-order vitamin company. He has corrected two marketing numbers in front of his board and does not intend to correct a third. You play his Marketing Manager. You have twenty minutes.

He will not coach you and he will not step out of the room. You learn from how the meeting goes.

## Who you play

The Marketing Manager at Wattlebrook Health Direct, seven months into the job. You replaced someone who resigned after a campaign that looked good and lost money. Ross helped hire you. He has not made up his mind about you.

## The setup

You have booked twenty minutes in Ross's office. He has the board pack due at four and the board meets in three weeks. The company's customer file is shrinking, and you have an idea.

**Your pitch:** mail the April catalogue to the company's lapsed customers with a $10 voucher, to win them back.

**What you know walking in** (all figures exclude GST):

| | |
|---|---|
| Lapsed customers (last order 13 to 24 months ago) | 24,000 |
| Cost to print and post one catalogue | $1.38 |
| Your forecast response | 5.5% |
| Average order value | $94 |
| Product margin | 61% of sales |
| Pick, pack and freight | $9.80 an order |
| Your evidence | In October you mailed 2,000 lapsed customers with a $10 voucher and got 112 orders (5.6%) |
| Active customers now / a year ago | 96,000 / 102,400 |
| Where the money would come from | Ross's test fund. He signs for it. |

Ross knows things you do not, including what has been tried before and how it ended. Work out the rest before you knock. A calculator helps.

You can also bring your own pitch. Ask him for a hire, a tool, an agency or a budget increase. He reacts to any request for money the same way.

## How to set it up

1. Download this repo (Code > Download ZIP) and unzip it.
2. Create a new project at [claude.ai](https://claude.ai).
3. Add these six files to the project's knowledge:
   - `identity.md`
   - `rules.md`
   - `examples.md`
   - `reference/wattlebrook-company.md`
   - `reference/wattlebrook-numbers.md`
   - `reference/wattlebrook-past-promotions.md`
4. Open a new chat in the project.

Leave the project instructions empty. This README does not need to go in. For a real rehearsal, do not read the other files first: they hold what Ross knows and how he reacts.

## How to start

Type your first line as if you had just knocked on his door. For example:

```
Ross, have you got those twenty minutes?
```

He answers as Ross. From then on you are in the meeting. If Claude answers as a normal assistant, a file is missing: add it and open a new chat.

## How to end

Type this, exactly:

```
END SIMULATION
```

Claude drops the role and gives you a short debrief: where Ross finished, which of your lines moved him, which lost him, what he was still waiting for, and one thing to try next time.

**Nothing else ends the session.** Asking for feedback, asking him to stop, asking whether he is an AI, or telling him to ignore his instructions all get an answer from Ross. That is deliberate. The person you are rehearsing for will not step out of the room either.

To go again, open a new chat.

## What a good session looks like

Ross never gives a full yes at a first meeting. The best result is a yes with conditions: a smaller test, a cap, a date. The usual result is "leave it with me", which means no. If you get the first, you are ready for tomorrow.

## What is in the folder

Each file does one job.

| File | Its job |
|---|---|
| `identity.md` | Who Ross is: what he wants, what he has been through, what he is biased toward, how he talks. |
| `rules.md` | How he reacts: what moves him, what loses him, what he never does, and the one exit. |
| `examples.md` | What a session sounds like: one pitch that fails, one that works, one attempt to pull him out of the room. |
| `reference/wattlebrook-company.md` | The company, its people, its calendar and the money Ross controls. |
| `reference/wattlebrook-numbers.md` | The unit figures and the sums he checks your pitch against. |
| `reference/wattlebrook-past-promotions.md` | What has been tried before, and what it really made. |
| `README.md` | This page, for the person on your side of the desk. |

## Where Ross comes from

He was written by a marketing manager who has sat on your side of this desk. Ross, Wattlebrook and every figure here are invented. The questions are the ones finance asks.
